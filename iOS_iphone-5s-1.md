#### Test 113351851151165c_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/2D23BEB3-2232-4DD8-B237-C6803E3B128D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2D23BEB3-2232-4DD8-B237-C6803E3B128D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65535"
,(lldb)     command script import "/tmp/2D23BEB3-2232-4DD8-B237-C6803E3B128D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-07-18 09:50:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:50:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:50:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:50:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:50:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:50:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:50:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests,.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B666F314-DFB3-4645-AA32-1868B2129F0F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B666F314-DFB3-4645-AA32-1868B2129F0F
,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9981D9E9-DE2E-45D9-B53B-9F59BB28C418
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A4F553E1-399A-4980-AB4D-9B5D70D1C08E
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71BF66F7-FCB8-4696-90AE-2D406F288DA3", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:71BF66F7-FCB8-4696-90AE-2D406F288DA3
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71BF66F7-FCB8-4696-90AE-2D406F288DA3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71BF66F7-FCB8-4696-90AE-2D406F288DA3", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-18 09:50:46 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.534357964992523
,2017-07-18 09:50:46 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-18 09:50:46 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:71BF66F7-FCB8-4696-90AE-2D406F288DA3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "71BF66F7-FCB8-4696-90AE-2D406F288DA3", generation: 0)
,2017-07-18 09:50:49 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-18 09:50:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-18 09:50:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-18 09:50:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-18 09:50:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-18 09:50:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-18 09:50:53 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-18 09:50:53 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-18 09:50:54 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-18 09:50:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-18 09:50:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-18 09:50:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-18 09:51:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-18 09:51:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-18 09:51:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-18 09:51:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-18 09:51:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 32 fourth
ok 33 second
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
,2017-07-18 09:51:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-18 09:51:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-18 09:51:10 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-18 09:51:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-18 09:51:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C66ADB62-5DB7-43D2-99C6-4EF887B9DA26
[ThaliCore] Browser.startListening
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:16 - INFO tha,l,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BF6C56F7-94B1-4026-90E4-A9ED772BB56C
[ThaliCore] Browser.startListening
2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:51:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:51:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BB74C60A-134C-4835-AF10-BB5EE18952D1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BB74C60A-134C-4835-AF10-BB5EE18952D1
2017-07-18 0,9:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BB74C60A-134C-4835-AF10-BB5EE18952D1
2017-07-18 09:51:19 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertis,ingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF9A5C86-0906-4689-9D4F-60643E4F1DA7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CF9A5C86-0906-4689-9D4F-60643E4F1DA7
2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(,onPort:errorHandler:) Peer(uuid: "CF9A5C86-0906-4689-9D4F-60643E4F1DA7", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:CF9A5C86-0906-4689-9D4F-60643E4F1DA7
2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingS,tateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":,false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CF9A5C86-0906-4689-9D4F-60643E4F1DA7
[ThaliCore] ,Advertiser.stopAdvertising() peerID:CF9A5C86-0906-4689-9D4F-60643E4F1DA7
2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:20 - INFO thaliM,o,bile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F2901452-AE22-4CB3-96E1-1C614499BC0E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F2901452-AE22-4CB3-96E1-1C614499BC0E
2017-07-18 0,9:51:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:118163B9-FF10-4208-8749-56E94D3DF4DC
[Thali,Core] Browser.startListening
2017-07-18 09:51:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:51:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:51:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80D74A42-61EC-45BE-AA90-5C1DF610E490:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80D74A42-61EC-45BE-AA90-5C1DF610E490", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADD621AC-46A0-4CE2-9B2B-724F599DC244:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD621AC-46A0-4CE2-9B2B-724F599DC244", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2901452-AE22-4CB3-96E1-1C614499BC0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2901452-AE22-4CB3-96E1-1C614499BC0E", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F2901452-AE22-4CB3-96E1-1C614499BC0E
2017-07-18 0,9:51:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 S,h,ould be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E7823D58-1DBC-4490-B24C-D54ABF468217
2017-07-18 0,9:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27
[ThaliCore] Browser.startListe,ning
2017-07-18 09:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:51:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
2017-07-18 09:51:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 60D5D6A0-54FF-41BD-9405-55F97D5EB615 (syncValue: aqqd1v0yw1y21UNxsdSGPZYqEC5zBeqE)'
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78520665-8F5D-47F2-B15B-379A15DC8B71
[ThaliCore] Advertiser: session connected Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:78520665-8F5D-47F2-B15B-379A15DC8B71 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57725109-4D9E-4D84-A112-79A625B1D5D7
[ThaliCore] Advertiser: session connected Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:57725109-4D9E-4D84-A112-79A625B1D5D7 state: notConnected -> connecting
2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5F321996-1BF0-489C-8C7,0,-3A82EC46FE51","generation":0}'
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57725109-4D9E-4D84-A112-79A625B1D5D7
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[Tha,liCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:78520665-8F5D-47F2-B15B-379A15DC8B71
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57725109-4D9E-4D84-A112-79A625B1D5D7 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:78520665-8F5D-47F2-B15B-379A15DC8B71 state: connecting -> connec,ted
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53124
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aqqd1v0yw1y21UNxsdSGPZYqEC5zBeqE","error":null,"portNumber":53124}'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aqqd1v0yw1y21UNxsdSGPZYqEC5zBeqE', error: 'null', listeningPort: '53124''
,2017-07-18 09:51:44 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,2017-07-18 09:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:51:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E7823D58-1DBC-4490-B24C-D54ABF468217
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53124
,[ThaliCore] Session.disconnect() peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:78520665-8F5D-47F2-B15B-379A15DC8B71 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:57725109-4D9E-4D84-A112-79A625B1D5D7
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:57725109-4D9E-4D84-A112-79A625B1D5D7
[ThaliCore] AdvertiserRelay.deinit
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1A0499C8-21DB-4F11-B792-A89F6B7556D1
2017-07-18 0,9:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:722798E2-AB6A-4C63-9A3F-E302DF92502A
[Tha,liCore] Browser.startListening
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:51:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5F321996-1BF0-489C-8C70-3A82EC46FE51","generation":0}'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5F321996-1BF0-489C-8C70-3A82EC46FE51 (syncValue: 4nOzjZkSgCwbfPR9gOtLVRcxt2ZpjkGf)'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","generation":0}'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","generation":0}'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"31978CED-B0AE-4798-B7C8-849267BE9E,39","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
,2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:51:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4nOzjZkSgCwbfPR9gOtLVRcxt2ZpjkGf","error":"Peer is unavailable",,"portNumber":null}'
2017-07-18 09:51:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4nOzjZkSgCwbfPR9gOtLVRcxt2ZpjkGf', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-18 09:51:48 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"5F321996-1BF0-489C-8C70-3A82EC46FE51","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:51:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-18 09:51:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier,":"5F321996-1BF0-489C-8C70-3A82EC46FE51","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:51:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:51:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-18 09:51:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 60D5D6A0-54FF-41BD-9405-55F97D5EB615 (syncValue: A6bqV6PSC4ht2zK6bRpAFHA,qmMhqJ0qt)'
2017-07-18 09:51:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97,D5EB615:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:51:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,0D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,0D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62
[ThaliCore] Advertiser: session connected Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,0D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:60D5D6A0,-54FF-41BD-9405-55F97D5EB615 error: max retries exceeded
2017-07-18 09:51:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"A6bqV6PSC4ht2zK6bRpAFHAqmMhqJ0qt","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:51:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'A6bqV6PSC4ht2zK6bRpAFHAqmMhqJ0qt', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:51:53 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:51:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-18 09:51:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60D5D6A0-54FF-41BD-9405-55F97D5EB615","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-18 09:51:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:51:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:51:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85ED1FFD-D50E-497A-9762-800969B8B575 (syncValue: sifQujZOXwy5y7qkblX97PpBHnaeHxwM)'
2017-07-18 09:51:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED,1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:51:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Session.deinit peer:6,0D5D6A0-54FF-41BD-9405-55F97D5EB615:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62
,[ThaliCore] Session.session(_:peer:didChange:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62
,[ThaliCore] Session.startOutputStream(with:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:51:54 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-18 09:51:54 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-18 09:51:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-18 09:51:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53134
2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sifQujZOXwy5y7qkblX97PpBHnaeHxwM",,"error":null,"portNumber":53134}'
2017-07-18 09:51:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sifQujZOXwy5y7qkblX97PpBHnaeHxwM', error: 'null', listeningPort: '53134''
Connecting to the localhost:53134
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,Connected to the localhost:53134
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:51:56 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-18 09:51:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:2 []
,ok 104 got the same data back
,# teardown
,2017-07-18 09:51:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1A0499C8-21DB-4F11-B792-A89F6B7556D1
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:85ED1FFD-D50E-497A-9762-800969B8B575
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectio,nsAndDisconnectClients() port:53134
[ThaliCore] Session.disconnect() peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F6EA1236-0D2D-403E-91A7-30A465099F62 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F6EA1236-0D2D-403E-91A7-30A465099F6,2
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:F6EA1236-0D2D-403E-91A7-30A465099F62
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2B7CA6F7-3F9F-4284-8D14-32237A26476F
2017-07-18 0,9:51:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F6DF7613-A4D4-463D-BA47-6615C92DA0C6
[ThaliCore] Browser.startListening
2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:51:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
2017-07-18 09:51:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","generation":0}'
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85ED1FFD-D50E-497A-9762-800969B8B575 (syncValue: Tgg7eFz0x0887C4eTGxMep7W9NrI3CTD)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31978CED-B0AE-4798,-B7C8-849267BE9E39:0
2017-07-18 09:51:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85,ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"31978CED-B0AE-4798-B7C8-849267BE9E39","generation":0}'
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15","generation":0}'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13A16B2D-9A9A-4856-BD41,-17E83D3985F1:0
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","generation":0}'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85,ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,5ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85,ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,5ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85,ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:85ED1FFD,-D50E-497A-9762-800969B8B575 error: max retries exceeded
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Tgg7eFz0x0887C4eTGxMep7W9NrI3CTD","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Tgg7eFz0x0887C4eTGxMep7W9NrI3CTD', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 31978CED-B0AE-4798-B7C8-849267BE9E39 (syncValue: Mt3amxp,XPL9LGsr8gIeXkStHbt0t9Z1u)'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
[ThaliCore] Advertiser: session connected Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,1978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,1978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
[ThaliCore] Session.startOutputStream(with:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
[ThaliCore] Session.startOutputStream(with:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
,[ThaliCore] Session.startOutputStream(with:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (5546 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (7168 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (456 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received all data: XSYZWsKl9G3XzPeDnQPaK7E7qKmNMzKj5DIYTqvTvIpvC9slYfwwW0aooss78h0T4JEJjiDjQpERqJl8a6GE9ppFpKy5LyHwLWedhQBEsSdnyE6TK7yirmDYLGkWcGlPemNvwNa0PKMveuj9igf82Lh679QAXTrmMlCwfxGqJnuo1zXQnS,c0r2J4UXEp4jG4js4k4y3TY2xt0KlyiyR1lMUGqpEvYFuTjcxNmNTpFQBib0mF4kq2fhOgJ2Dx6fMcMNKFQyEIDs5Tsuq6s4gcg7xsctES7qDrayhFLGfcIDSOphJVgUukPaxtYsBpCYiKxkNSWHlLzdnuK9GxjRvjJcqk5cIiDIQG2nFnJfAUJOrtoeWQMBKCeVZtY2QCi5J4V1mMdutwwRNfwmiO19nZVn5lvlq5Tl6tyuQnIJArHZrfcYWmhf,T67XH8isSV5RhAgD2JfQtLbg2jbcJyIPvbvQoxwC3iny1ndxvXlVEFr6f1RQKdnkrNG0V9oHEXTyJZLmEZZ9xqtqnwsfWFn3AvGpbin2M1v3FbGUnPTUb2B8WJEvf7AxrOzGa2fso56aj6tB23j3A8Lxb1TAFPXLyZs3o0g3TJjLMB9Qrn4zT7DiuXFkthRQvwHhKTiiJG2RT7LHPxFrvTsSrxKmP5vQheZ2QBWgycZM14BwIbAkV31EBCGOzIEm,62rP7JyTkrtNXvKtwd2itGa8nEGLJAz1LNZTJO6N9xwUahNy81T9hxTKZmYokG2etLjgK91qFicateqABLcLh1JXUvRZqFmPEG8zT0uDDyVRAB8NvzHV9H7DdMpUDaz3gpldEtQHdKGX25UhmXpu4RqqfnfEPGUJOezdiXt2CGkLNNMlwIyEtmNWmLeRAjHelcnjyCqACnjnF6JT6eiBUIIbS4xX3lNin3qz7JrzyZVOdTDaZoR0bXx3KTA5n72,5,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,T,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'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,978CED-B0AE-4798-B7C8-849267BE9E39:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] Session.deinit peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [3, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [3]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:31978CED,-B0AE-4798-B7C8-849267BE9E39 error: max retries exceeded
2017-07-18 09:52:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Mt3amxpXPL9LGsr8gIeXkStHbt0t9Z1u","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Mt3amxpXPL9LGsr8gIeXkStHbt0t9Z1u', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:06 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"31978CED-B0AE-4798-B7C8-849267BE9E39","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"31978CED-B0AE-4798-B7C8-849267BE9E39","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:06 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15 (syncValue: qbzub4m,0utaMLlirE4nm0F9ULUATGOFs)'
2017-07-18 09:52:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6FF1C5AC-E652,-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:52:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-18 09:52:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53150
2017-07-18 09:52:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qbzub4m0utaMLlirE4nm0F9ULUATGOFs",,"error":null,"portNumber":53150}'
2017-07-18 09:52:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qbzub4m0utaMLlirE4nm0F9ULUATGOFs', error: 'null', listeningPort: '53150''
,Connecting to the localhost:53150
Connecting to the localhost:53150
Connecting to the localhost:53150
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
Connected to the localhost:53150
[ThaliCore] ,BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] Session.startOutputStream(with:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
,Connected to the localhost:53150
Connected to the localhost:53150
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-18 09:52:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [3, 7, 8]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [3, 8]
,ok 112 got the same data back
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [3]
,ok 114 got the same data back
,# teardown
,2017-07-18 09:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2B7CA6F7-3F9F-4284-8D14-32237A26476F
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53150
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qbzub4m0utaMLlirE4nm0F9ULUATGOFs","error":"Session disconnected","portNumber":null}'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
[ThaliCore] Session.session(_:peer:didChange:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] ,AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
[ThaliCor,e] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:74EEA8D0-8560-4241-8408-D752D9A14577
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:901B53B2-11CD-46AE-B53A-5093A88750C6
,[ThaliCore] Browser.startListening
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
2017-07-18 09:52:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","generation":0}'
,2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 13A16B2D-9A9A-4856-BD41-17E83D3985F1 (syncValue: hBXPtkESE755s7VSAaTfDNculmUWf8Bd)'
,2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
2017-07-18 09:52:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"624396A9-3501-4E23-BC49-2F10FDE3AE33","generation":0}'
2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:12 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", g,eneration: 0)
2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7DE26A7A-5E15-49DC-9309-AE715C12E4A1","generation":0}'
2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running ,test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
,2017-07-18 09:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:13A16B2D,-9A9A-4856-BD41-17E83D3985F1 error: max retries exceeded
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hBXPtkESE755s7VSAaTfDNculmUWf8Bd","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hBXPtkESE755s7VSAaTfDNculmUWf8Bd', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"13A16B2D-9A9A-4856-BD41-17E83D3985F1","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 624396A9-3501-4E23-BC49-2F10FDE3AE33 (syncValue: mLcstRk,PwJbMJvULhhesISUAM4QweXvB)'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:624396A9-3501,-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53161
,2017-07-18 09:52:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mLcstRkPwJbMJvULhhesISUAM4QweXvB","error":null,"portNumber":53161}'
,2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mLcstRkPwJbMJvULhhesISUAM4QweXvB', error: 'null', listeningPort: '53161''
,Connecting to the localhost:53161
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:53161
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [3]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA
[ThaliCore] Advertiser: session connected Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA
,[ThaliCore] Session.startOutputStream(with:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-18 09:52:27 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-18 09:52:27 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-18 09:52:27 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-18 09:52:27 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-18 09:52:27 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeS,treams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [3]
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA
,2017-07-18 09:52:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 ,09:52:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-18 09:52:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising() peerID:74EEA8D0-8560-4241-8408-D752D9A14577
2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:28 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:624396A9-3501-4E23-BC49-2F10FDE3AE33
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53161
[ThaliCore] Session.disconnect() p,eer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:74526F95-007E-4B61-843A-4180389BA28D
,2017-07-18 09:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023
[ThaliCore] Browser.startList,ening
2017-07-18 09:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:52:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
,2017-07-18 09:52:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9","generation":0}'
,2017-07-18 09:52:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9 (syncValue: P8GMzbh4kedGCHHkWfHZ9Mg0DOTKg7W0)'
,2017-07-18 09:52:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:74526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
2017-07-18 09:52:31 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA7FABF7-B03B-465A-91E3-B2E4B0213751","generation":0}'
2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:31 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53167
2017-07-18 09:52:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P8GMzbh4kedGCHHkWfHZ9Mg0DOTKg7W0",,"error":null,"portNumber":53167}'
2017-07-18 09:52:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'P8GMzbh4kedGCHHkWfHZ9Mg0DOTKg7W0', error: 'null', listeningPort: '53167''
Connecting to the localhost:53167
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,Connected to the localhost:53167
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 124 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [3]
# teardown
,2017-07-18 09:52:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:74526F95-007E-4B61-843A-4180389BA28D
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53167
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P8GMzbh4kedGCHHkWfHZ9Mg0DOTKg7W0","error":"Session disconnected","portNumber":null}'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
,[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:865FC688-3CF6-4B92-BA1D-535320ADE495
,[ThaliCore] Browser.startListening
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F56E88A8-5367-48DD-834E-AA7C5F9B74B3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F56E88A8-5367-48DD-834E-AA7C5F9B74B3
,2017-07-18 09:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:52:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
2017-07-18 09:52:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EA7FABF7-B03B-465A-91E3-B2E4B0213751","generation":0}]'
2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"EA7FABF7-B03B-465A-91E3-B2E4B0213751","generation":0}'
2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"EA7FABF7-B03B-465A-91E3-B2E4B0213751","generation":0}]'
2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"EA7FABF7-B03B-465A-91E3-B2E4B0213751","generation":0}'
2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] Br,owser.browser(_:foundPeer:withDiscoveryInfo:) found peer:960D2F62-7D6D-4B13-B832-850740724523:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0)
2017-07-18 09:52:39 - DEBUG thaliMobileNat,iveWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"960D2F62-7D6D-4B13-B832-850740724523","generation":0}]'
,2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"960D2F62-7D6D-4B13-B832-850740724523","generation":0}'
2017-07-18 09:52:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F56E88A8-5367-48DD-834E-AA7C5F9B74B3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F56E88A8-5367-48DD-834E-AA7C5F9B74B3", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 ,09:52:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising() peerID:F56E88A8-5367-48DD-834E-AA7C5F9B74B3
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:44 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-18 09:52:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8CA9D11A-7513-4B60-B23A-1EDE50EF4B30
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5D035D3C-33B5-4B7C-B74A-B1C4E4F7B902", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5D035D3C-33B5-4B7C-B74A-B1C4E4F7B902
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5D035D3C-33B5-4B7C-B74A-B1C4E4F7B902
,ok 139 discoveryActive should be false
,ok 140 advertisingActive should be true
,ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-18 09:52:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 145 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-18 09:52:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 147 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-18 09:52:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-18 09:52:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-18 09:52:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 153 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-18 09:52:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 155 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:71e90cdc-d698-44c7-97f6-11be3e9b4488 error: startListeningNotActive
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"NJRR78oFVkCJruxoeXn4Puu02ryaGd1e","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"71e90cdc-d698-44c7-97f6-11be3e9b4488","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"71e90cdc-d698-44c7-97f6-11be3e9b4488","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 161 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
,2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:07B48751-3F7C-4820-98A7-626BE7C3FEA3
[ThaliCore] Browser.startListening
2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:52:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 No error on star,ting
ok 164 Got null as expected
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"x1nmTOPBnSi3zd1nfVTDu8B4orvpkfHi","error":"Illegal peerID","portNumber":null}'
ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-18 09:52:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC9AFD2B-F02D-4894-86E4-9D20AB5997D6
[ThaliCore] Browser.startListening
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 No error on star,ting
,ok 174 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 175 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 176 Should be able to call stopAdvertisingAndListening in teardown
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: ,'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectRes,olved registered to native'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAc,tive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:2411d842-2515-4f10-8c75-68a762891111
ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 181 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 182 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:730E3CE2-CE3F-4684-B97C-85BAE4444C28
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 183 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB
,[ThaliCore] Browser.startListening
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 184 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EE1ADE94-333C-449C-BB6D-D3402DE39710:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EE1ADE94-333C-449C-BB6D-D3402DE39710", generation: 0)
2017-07-18 09:52:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B68E1B2B-5D40-46BE-92E9-A865509D6EEF","generation":0}'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B68E1B2B-5D40-46BE-92E9-A865509D6EEF (syncValue: oy30Ls5DgNpY5SEULmcO0Z2jrEuXs4tF)'
2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EE1ADE94-333C-449C-BB6D-D3402DE39710","generation":0}'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51
[ThaliCore] Advertiser: session connected Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51
[ThaliCore] Session.startOutputStream(with:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53175
2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oy30Ls5DgNpY5SEULmcO0Z2jrEuXs4tF",,"error":null,"portNumber":53175}'
2017-07-18 09:52:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oy30Ls5DgNpY5SEULmcO0Z2jrEuXs4tF', error: 'null', listeningPort: '53175''
,ok 185 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0) found active relay
2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'multiConn,ectResolved: {"syncValue":"xZ8BPK1R5I9ho08sDlqTv7BUl5v8lBjH","error":null,"portNumber":53175}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B6,8E1B2B-5D40-46BE-92E9-A865509D6EEF:0
ok 186 No error
ok 187 Ports equal
,ok 188 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0) found active relay
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Cye4lbPJD92SH4PW4GeEvxOUR5z05PqR","error":null,"portNumber":53175}'
,ok 189 No error
,ok 190 Ports equal
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 12, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F
[ThaliCore] Advertiser: session connected Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F
[ThaliCore] Session.startOutputStream(with:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [3, 12, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:53:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 191 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:730E3CE2-CE3F-4684-B97C-85BAE4444C28
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNo,nTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 192 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] T,CPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserManager.disconnect peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescr,iption=Socket closed by remote peer})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53175
[ThaliCore] Session,.session(_:peer:didChange:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F state: connected -> notConnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] AdvertiserRel,ay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] Advertiser: session notConnected Peer(uuid: "730E3CE2-CE3,F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] TCPClient.deinit
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] Session.disconnect() peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.disconnect() peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] TCPListener.deinit
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:14 [3, 12, 13]
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
[ThaliCore] VirtualSocket.deinit vsID:12 [3, 13]
[ThaliCore] VirtualSocket.deinit vsID:13 [3]
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0DBDBF9-7E02-4274-B5F9-C07573030C51 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F
,# initial peer discovery
,2017-07-18 09:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-18 09:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-18 09:53:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'listening 53179'
,ok 193 Should throw
,# teardown
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'listening 53181'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 194 initial connection state should be CONNECTED
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 195 final connection state should be DISCONNECTED
,# teardown
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'listening 53184'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 196 tried to connect to right port
,ok 197 failed due to refused connection
,ok 198 routerPortConnectionFailed is emitted
,# teardown
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'listening 53188'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 199 Send/recvd #1 should be equal length
,ok 200 Send/recvd #1 should be same
,ok 201 Send/recvd #2 should be equal length
,ok 202 Send/recvd #2 should be same
,ok 203 Should be exactly 2 client sockets
,# teardown
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 53193'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 204 socket shouldn't close until after stream
,ok 205 incoming remains open
,# teardown
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 53197'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 206 we should not have gotten an error
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 207 socket shouldn't close until after incoming
,ok 208 incoming is cleaned up
,# teardown
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 53201'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 209 stream was closed
,ok 210 incoming should survive
,ok 211 mux should have no streams
,# teardown
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 53205'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 212 we should not have gotten an error
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 213 Buffers are identical
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 214 native server is nulled out
,ok 215 native server should be closed
,ok 216 incoming has been removed
,ok 217 Incoming should be done
,ok 218 The mux object should be closed
,ok 219 The mux stream should be closed
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:07 - DEBUG createNativeListener: 'listening 53209'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-18 09:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 220 native server is nulled out
,ok 221 native server should be closed
,ok 222 incoming has been removed
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-18 09:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'listening 53261'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 223 we should not have gotten an error
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 224 Buffers are identical
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 225 server should be fine
,ok 226 server should be open
,ok 227 incoming has been removed
,ok 228 The mux object should be closed
,ok 229 The mux stream should be closed
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'listening 53265'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 230 we should not have gotten an error
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 231 Buffers are identical
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 232 server should be fine
,ok 233 server should be open
,ok 234 incoming has been removed
,ok 235 The mux object should be closed
,ok 236 The mux stream should be closed
,# teardown
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 237 serversManager must not be null
ok 238 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 239 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 53268'
,ok 240 port must be in range
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 53269'
,ok 241 second start should return same port
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 53271'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 242 we should be connected
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 243 now we are disconnected
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 244 Passed bogus id
,2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 245 Passed good id but bogus port
,2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 246 Passed right context
,ok 247 Right server
,ok 248 No error should be set
,ok 249 Retry should be false
,ok 250 We called close server
,# teardown
,# setup
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single local http request
,listening on 53273
,ok 251 should be equal
,# teardown
,2017-07-18 09:53:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7E3D0BB5-4FA3-4194-9297-87098529DE9A
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 252 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] Browser.startList,ening
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}'
2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6058E2A,4-FAC9-450F-81D5-E68925F48B59 (syncValue: UWJd47wfaSHiLU5UM7oJYMKOQceVJpQc)'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60,58E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}'
2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53278
,2017-07-18 09:53:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UWJd47wfaSHiLU5UM7oJYMKOQceVJpQc","error":null,"portNumber":53278}'
2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U,WJd47wfaSHiLU5UM7oJYMKOQceVJpQc', error: 'null', listeningPort: '53278''
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connecting -> connected
,ok 254 should be equal
,2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B77BB749-103B-4479-A004-5B3078040F60 (syncValue: 2Xv2aDPPAdI5HjFDc4mmLhC76kh8yQDu)'
,2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B77BB749-103B-4479-A004-5B3078040F60:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
[ThaliCore] Advertiser: session connected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53282
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2Xv2aDPPAdI5HjFDc4mmLhC76kh8yQDu","error":null,"portNumber":53282}'
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2Xv2aDPPAdI5HjFDc4mmLhC76kh8yQDu', error: 'null', listeningPort: '53282''
,ok 255 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:6058E2A4-FAC9-450F-81D5-E68925F48B59
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53278
[ThaliCore] Session.disconnect() p,eer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:B77BB749-103B-4479-A004-5B3078040F60
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:53282
[ThaliCore] Session.disconnect() peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,2017-07-18 09:53:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple local http requests
,listening on 53284
,[ThaliCore] Session.deinit peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,ok 256 should be equal
,ok 257 should be equal
,ok 258 should be equal
,# teardown
,2017-07-18 09:53:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:7E3D0BB5-4FA3-4194-9297-87098529DE9A
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 259 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 260 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":1}'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6058E2A4-FAC9-450F-81D5-E68925F48B59 (syncValue: KWgtcNw1DYvJRCpdxVSylp2ML8jNmDrf)'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
[ThaliCore] Advertiser: session connected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53293
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KWgtcNw1DYvJRCpdxVSylp2ML8jNmDrf","error":null,"portNumber":53293}'
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KWgtcNw1DYvJRCpdxVSylp2ML8jNmDrf', error: 'null', listeningPort: '53293''
,ok 261 should be equal
,ok 262 should be equal
,ok 263 should be equal
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B77BB749-103B-4479-A004-5B3078040F60 (syncValue: hQ8lE1B8zK66Gf3QqiFfEHx3ZNNKDRIk)'
,2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
[ThaliCore] Advertiser: session connected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53302
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,2017-07-18 09:53:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hQ8lE1B8zK66Gf3QqiFfEHx3ZNNKDRIk","error":null,"portNumber":53302}'
,2017-07-18 09:53:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hQ8lE1B8zK66Gf3QqiFfEHx3ZNNKDRIk', error: 'null', listeningPort: '53302''
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connecting -> connected
,ok 264 should be equal
,ok 265 should be equal
,ok 266 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:6058E2A4-FAC9-450F-81D5-E68925F48B59
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53293
[ThaliCore] TCPListener.socketDidD,isconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
[ThaliCore] Sessio,n.session(_:peer:didChange:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A state: connected -> notConnected
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] Session.deinit peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:B77BB749-103B-4479-A004-5B3078040F60
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53302
,[ThaliCore] Session.disconnect() peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:53:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] Session.deinit peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 267 specific error should be returned
,# teardown
,ok 268 must be stopped
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 269 specific error should be returned
,# teardown
,ok 270 must be stopped
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 53306'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7E3D0BB5-4FA3-4194-9297-87098529DE9A
,[ThaliCore] Advertiser.stopAdvertising() peerID:7E3D0BB5-4FA3-4194-9297-87098529DE9A
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 273 must be stopped
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 53307'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:77C169C6-BBB2-43E2-8B5C-6EFADE874DF9
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 274 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisi,ngActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router,":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 275 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-18 09:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 53308'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6624A4FA-37BF-4967-9E6E-F643F40DA2B3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6624A4FA-37BF-4967-9E6E-F643F40DA2B3
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 277 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6624A4FA-37BF-4967-9E6E-F643F40DA2B3", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:6624A4FA-37BF-4967-9E6E-F643F40DA2B3
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 278 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6624A4FA-37BF-4967-9E6E-F643F40DA2B3
,[ThaliCore] Advertiser.stopAdvertising() peerID:6624A4FA-37BF-4967-9E6E-F643F40DA2B3
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 279 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 53311'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 280 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 281 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 282 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 283 network status should have certain non-empty properties
,# teardown
,ok 284 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-18 09:53:38 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 285 specific error expected
,# teardown
,ok 286 must be stopped
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 53312'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A604455-F0FA-43EC-88A7-A7C560581CBC
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "043A4762-9359-4AC0-85B9-7FADE83C2130", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:043A4762-9359-4AC0-85B9-7FADE83C2130
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 287 all connection succeed
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
2017-07-18 09:53:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-,4479-A004-5B3078040F60", generation: 0)
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}'
2017-07-18 09:53:3,8 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}]'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}]'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:043A4762-9359-4AC0-85B9-7FADE83C2130
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 288 must be stopped
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 53315'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A3A9BFCF-56E8-40BA-A461-0C7C17C75746
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0E778248-311E-4A0C-ABE6-E33A9485F6CA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0E778248-311E-4A0C-ABE6-E33A9485F6CA
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:38 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType,":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 289 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
2017-07-18 09:53:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}]'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}]'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0E778248-311E-4A0C-ABE6-E33A9485F6CA
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 290 must be stopped
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'listening 53317'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:23047AF8-1227-4EE7-B1CE-B720B125D1A3
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E522508B-8AE9-4FF4-97F7-5CC68752B219", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E522508B-8AE9-4FF4-97F7-5CC68752B219
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E522508B-8AE9-4FF4-97F7-5CC68752B219
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 291 is stopped after calling stop
,ok 292 connection should fail after stopping
,# teardown
,ok 293 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-18 09:53:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 294 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 295 error description matches
,# teardown
,ok 296 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-18 09:53:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 297 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 298 error description matches
,# teardown
,ok 299 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 300 IMPLEMENT ME!!!!!!
,# teardown
,ok 301 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 302 must be stopped
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 303 must be stopped
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 304 must be stopped
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 305 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 306 NOT IMPLEMENTED # SKIP
,# teardown
,ok 307 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-18 09:53:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 308 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-18 09:53:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 309 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-18 09:53:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 310 must be stopped
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-18 09:53:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 311 must be stopped
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 53320'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5F772334-BC94-436B-B324-E48D14A96036
[ThaliCore] Browser.startListening
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 312 discoveryActive ,matches
,ok 313 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 314 discoveryActive matches
ok 315 advertisingActive matches
,2017-07-18 09:53:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 53321'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FAB41FDF-4024-4F9E-9807-3C0C485F4351", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FAB41FDF-4024-4F9E-9807-3C0C485F4351
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 316 discoveryActive matches
,ok 317 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FAB41FDF-4024-4F9E-9807-3C0C485F4351
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 318 discoveryActive matches
ok 319 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'listening 53323'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 320 must be stopped
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'listening 53324'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:74C69500-66CF-46AF-B84C-DBD650C7B5D8
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "272864CE-F177-432F-A2F8-84DFFD462ED2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:272864CE-F177-432F-A2F8-84DFFD462ED2
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81,D5-E68925F48B59","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Pee,r(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60",",generation":1}]'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}]'
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 321 portNumber equal null
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:272864CE-F177-432F-A2F8-84DFFD462ED2
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 must be stopped
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'listening 53326'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C3E224A1-2594-49C9-BC04-CA81D35463B0
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}]'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}]'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}]'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6058E2A4-FAC9-450F-81D5-E68925F48B59 (syncValue: QYy942GBGyMuiEsEL6bsEhz2bARMx5av)'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QYy942GBGyMuiEsEL6bsEhz2bARMx5av","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QYy942GBGyMuiEsEL6bsEhz2bARMx5av', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B77BB749-103B-4479-A004-5B3078040F60 (syncValue: bSJQ8fQSEIuNOL6jaO5ulGzH4zb6eCOX)'
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,7BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,77BB749-103B-4479-A004-5B3078040F60", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF:0
2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF", generation: 0)
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:53:46 - ,DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","generation":0}]'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","generation":0}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:53:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,7BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,77BB749-103B-4479-A004-5B3078040F60", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,7BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,77BB749-103B-4479-A004-5B3078040F60", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:1
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B77BB749-103B-4479-A004-5B3078040F60:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,7BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B77BB749,-103B-4479-A004-5B3078040F60 error: max retries exceeded
2017-07-18 09:53:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bSJQ8fQSEIuNOL6jaO5ulGzH4zb6eCOX","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:53:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bSJQ8fQSEIuNOL6jaO5ulGzH4zb6eCOX', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:53:49 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:53:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:53:49 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:53:49 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:53:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:53:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,ier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:53:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 953E254B-C59F-49CE-9D01-EB3331406366 (syncValue: P4Uq8Vf04CFuOruxoWKycfQg0PU9hcvB)'
,2017-07-18 09:53:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2
[ThaliCore] Advertiser: session connected Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D
[ThaliCore] Advertiser: session connected Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53337
,2017-07-18 09:53:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P4Uq8Vf04CFuOruxoWKycfQg0PU9hcvB","error":null,"portNumber":53337}'
,2017-07-18 09:53:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'P4Uq8Vf04CFuOruxoWKycfQg0PU9hcvB', error: 'null', listeningPort: '53337''
,2017-07-18 09:53:53 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:53:53 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:53:53 - DEBUG testUtils: 'Got end'
,ok 323 response body should match testData
,ok 324 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D
,[ThaliCore] Session.startOutputStream(with:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 15, 16]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2
[ThaliCore] Session.startOutputStream(with:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [3, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-18 09:53:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketS,treamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [3, 15, 17]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsy,ncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler d,isconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore], VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [3, 15]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [3]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D
,[ThaliCore] AdvertiserRelay.deinit
,ok 325 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:953E254B-C59F-49CE-9D01-EB3331406366
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53337
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:953E254B-C59F-49CE-9D01-EB3331406366:0
,[ThaliCore] Session.deinit peer:953E254B-C59F-49CE-9D01-EB3331406366:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD136716-2FE8-43A2-AD73-6E23245E33A2 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D
,# can still do HTTP requests between peers with coordinator
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'listening 53341'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42D5359B-CE1E-433D-BB41-8294E9596A99
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3BAEA213-54FC-4444-8A5D-A5BD960AADD9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3BAEA213-54FC-4444-8A5D-A5BD960AADD9
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peer,Identifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"953E,254B-C59F-49CE-9D01-EB3331406366","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged ,event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3BAEA213-54FC-4444-8A5D-A5BD960AADD9:0
2017-07-18 09:53:55 - D,EBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3BAEA213-54FC-4444-8A,5D-A5BD960AADD9", generation: 0)
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}]'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":0}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 953E254B-C59F-49CE-9D01-EB3331406366 (syncValue: a7hJveI9d9kz2vFZy8vTJe8wpVlwvy9i)'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}]'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,3E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,53E254B-C59F-49CE-9D01-EB3331406366", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,3E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,53E254B-C59F-49CE-9D01-EB3331406366", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
2017-07-18 09:53:58 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}]'
2017-07-18 09:53:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","generation":1}'
,2017-07-18 09:53:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:53:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B77BB749-103B-4479-A004-5B3078040F60","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,3E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,53E254B-C59F-49CE-9D01-EB3331406366", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:953E254B-C59F-49CE-9D01-EB3331406366:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,3E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:953E254B,-C59F-49CE-9D01-EB3331406366 error: max retries exceeded
2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"a7hJveI9d9kz2vFZy8vTJe8wpVlwvy9i","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:54:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'a7hJveI9d9kz2vFZy8vTJe8wpVlwvy9i', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:54:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 832961D1-12F0-4253-9FBC-B054D32A0095 (syncValue: aR5oiAHmIFMqO5zqK4LD8bZCebk6G9R3)'
,2017-07-18 09:54:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}]'
2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}'
,2017-07-18 09:54:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-18 09:54:00 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53350
2017-07-18 09:54:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aR5oiAHmIFMqO5zqK4LD8bZCebk6G9R3",,"error":null,"portNumber":53350}'
2017-07-18 09:54:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aR5oiAHmIFMqO5zqK4LD8bZCebk6G9R3', error: 'null', listeningPort: '53350''
,2017-07-18 09:54:03 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [3, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:54:04 - DEBUG testUtils: 'Got response data'
2017-07-18 09:54:04 - DEBUG testUtils: 'Got end'
,ok 326 response body should match testData
ok 327 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3BAEA213-54FC-4444-8A5D-A5BD960AADD9
2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:54:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-07-18 09:54:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 328 must be stopped
[ThaliCore] BrowserManager.disconnect peer:832961D1-12F0-4253-9FBC-B054D32A0095
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53350
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] Session.disconnect() peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:18 [3]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-18 09:54:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 329 must be stopped
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 330 must be stopped
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'listening 53352'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BCCC528E-079E-40F9-9B63-457B4ACDBF3C
,[ThaliCore] Browser.startListening
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7715A4C7-4E63-4CF7-ACF2-CA28E269C078
2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:54:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
2017-07-18 09:54:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}]'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
2017-07-18 09:54:06 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 832961D1-12F0-4253-9FBC-B054D32A0095 (syncValue: ZdTFj0tsUc27Ct0,biFmqsnj7G5wXdqzm)'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}]'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
2017-07-18 09:54:07 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}]'
2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:07 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:54:07 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}]'
2017-07-18 09:54:07 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:83,2961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,32961D1-12F0-4253-9FBC-B054D32A0095", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:83,2961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,32961D1-12F0-4253-9FBC-B054D32A0095", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:83,2961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,32961D1-12F0-4253-9FBC-B054D32A0095", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
,2017-07-18 09:54:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}]'
,2017-07-18 09:54:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","generation":0}'
,2017-07-18 09:54:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:54:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA048616-D84D-433B-A13F-489E42F417AC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:83,2961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:832961D1,-12F0-4253-9FBC-B054D32A0095 error: max retries exceeded
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZdTFj0tsUc27Ct0biFmqsnj7G5wXdqzm","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:54:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZdTFj0tsUc27Ct0biFmqsnj7G5wXdqzm', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with ,{"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:10 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:54:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:54:10 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 50E8281F-8162-4C2A-8FC0-78964F5A9464 (syncValue: qUNTVx1pNiWlK4KckIRFGZXic99Ua2tK)'
,2017-07-18 09:54:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:455253BF-790E-4685-9B40-0827214A43F8
[ThaliCore] Advertiser: session connected Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:455253BF-790E-4685-9B40-0827214A43F8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53368
2017-07-18 09:54:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qUNTVx1pNiWlK4KckIRFGZXic99Ua2tK",,"error":null,"portNumber":53368}'
2017-07-18 09:54:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qUNTVx1pNiWlK4KckIRFGZXic99Ua2tK', error: 'null', listeningPort: '53368''
,2017-07-18 09:54:14 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [3, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:455253BF-790E-4685-9B40-0827214A43F8
,[ThaliCore] Session.session(_:peer:didChange:) peer:455253BF-790E-4685-9B40-0827214A43F8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:455253BF-790E-4685-9B40-0827214A43F8
,[ThaliCore] Session.startOutputStream(with:) peer:455253BF-790E-4685-9B40-0827214A43F8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [3, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:54:14 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:14 - DEBUG testUtils: 'Got end'
,ok 331 response body should match testData
,ok 332 must be started
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
,2017-07-18 09:54:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}]'
,2017-07-18 09:54:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}'
,2017-07-18 09:54:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:54:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7715A4C7-4E63-4CF7-ACF2-CA28E269C078
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:54:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-18 09:54:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 333 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:50E8281F-8162-4C2A-8FC0-78964F5A9464
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53368
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocke,tErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconne,cting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] Session.disconnect() peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] VirtualSocket.cl,oseStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] VirtualSocket.deinit vsID:19 [3, 20]
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonT,CP registered to native'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] BrowserRelay.deinit
[ThaliCore] VirtualSocket.deinit vsID:20 [3]
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:455253BF-790E-4685-9B40-0827214A43F8 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:455253BF-790E-4685-9B40-0827214A43F8
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,[ThaliCore] Session.deinit peer:455253BF-790E-4685-9B40-0827214A43F8
,ok 334 FIX ME, PLEASE!!!
,# teardown
,ok 335 must be stopped
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-18 09:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 336 must be stopped
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-18 09:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 337 must be stopped
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 338 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 339 specific error should be returned
,# teardown
,2017-07-18 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 340 error should be null
,ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 343 specific error should be returned
,# teardown
,ok 344 error should be null
ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 53371'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 347 error should be null
,ok 348 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 349 error should be null
,ok 350 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 351 error should be null
,ok 352 error should be null
,# setup
,ok 353 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 53372'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B309F0EB-D619-4039-9507-AC7BB48791E1
,[ThaliCore] Browser.startListening
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 354 error should be null
,ok 355 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 356 error should be null
,ok 357 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 53373'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "66ADA6D4-B6B5-40E4-8086-0E44598E3C56", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:66ADA6D4-B6B5-40E4-8086-0E44598E3C56
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 361 error should be null
ok 362 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "66ADA6D4-B6B5-40E4-8086-0E44598E3C56", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:66ADA6D4-B6B5-40E4-8086-0E44598E3C56
2017-07-18 0,9:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 363 error should be null
ok 364 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:66ADA6D4-B6B5-40E4-8086-0E44598E3C56
,[ThaliCore] Advertiser.stopAdvertising() peerID:66ADA6D4-B6B5-40E4-8086-0E44598E3C56
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 365 error should be null
,ok 366 error should be null
,# setup
,ok 367 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 53376'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 368 error should be null
,ok 369 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 370 error should be null
,ok 371 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-18 09:54:21 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 375 This should not cause wifi to fail
,ok 376 native router should be bad
,# teardown
,ok 377 error should be null
,ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-18 09:54:22 - DEBUG thaliMobileNativeWrapper: 'listening 53377'
ok 380 first call should succeed
ok 381 first call should succeed
,ok 382 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 383 error should be null
,ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-18 09:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 386 error should be null
,ok 387 error should be null
,# setup
,ok 388 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-18 09:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-18 09:54:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"403e9ce0-d7fd-4b14-a6bd-db94f0877531","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 392 should be called once
,ok 393 should not have been called more than once
,# teardown
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"403e9ce0-d7fd-4b14-a6bd-db94f0877531","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 394 error should be null
ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# can get the network status
,ok 397 network status should have certain non-empty properties
,# teardown
,ok 398 error should be null
ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 401 we have not added peer to the cache yet
2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"203de067-b22a-4bc2-89d0-53954f85a04d","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 402 peer should be available
ok 403 cache contains native peer
2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"203de067-b22a-4bc2-89d0-53954f85a04d","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 404 peer should be unavailable
ok 405 peer has been removed from cache
,# teardown
,ok 406 error should be null
ok 407 error should be null
,# setup
,ok 408 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 409 we have not added peer to the cache yet
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4b352196-ec12-4ec8-9881-aefb878becd5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 peer should be available
,ok 411 cache contains wifi peer
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4b352196-ec12-4ec8-9881-aefb878becd5","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 412 peer should be unavailable
,ok 413 peer has been removed from cache
,# teardown
,ok 414 error should be null
,ok 415 error should be null
,# setup
,ok 416 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec0791c1-2635-4183-b00e-13a74a1e1f90","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 417 first peer is available
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dcca6c43-1567-48a3-9d56-913a8ce08366","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 418 second peer is available
,ok 419 first and second peers are different
,# teardown
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ec0791c1-2635-4183-b00e-13a74a1e1f90","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dcca6c43-1567-48a3-9d56-913a8ce08366","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 420 error should be null
ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 423 should not be in cache at start
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f10d0f2d-4032-4190-8c81-de8872f7be7c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 peer is available
,# teardown
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f10d0f2d-4032-4190-8c81-de8872f7be7c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 error should be null
,ok 426 error should be null
,# setup
,ok 427 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-18 09:54:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-18 09:54:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 431 error should be null
,ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b2c85536-e7e0-4c46-86a6-f1a320030983","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 434 peer should be available
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b2c85536-e7e0-4c46-86a6-f1a320030983","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 435 peer should be ,available
ok 436 should store correct generation
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b2c85536-e7e0-4c46-86a6-f1a320030983","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 437 error should be null
ok 438 error should be null
,# setup
,ok 439 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'listening 53378'
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0aa3cb83-26be-4dd4-8fca-b378ea8a52ee","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 440 discovered correct peer
,ok 441 got correct generation
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0aa3cb83-26be-4dd4-8fca-b378ea8a52ee","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 442 discovered correct peer
,ok 443 got correct generation
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0aa3cb83-26be-4dd4-8fca-b378ea8a52ee","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 444 error should be null
,ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'listening 53379'
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b02f1811-fd5c-4e87-a857-7716567b4e56","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 447 discovered available peer
,ok 448 peer is available
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b02f1811-fd5c-4e87-a857-7716567b4e56","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 449 error should be null
,ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3cb5922c-891a-4abb-8975-3212f82b57e9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 452 peer should be available
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3cb5922c-891a-4abb-8975-3212f82b57e9","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 453 peer should be unavailable
,ok 454 should be removed from cache
,# teardown
,ok 455 error should be null
,ok 456 error should be null
,# setup
,ok 457 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 53380'
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"09fef3ab-62bc-49cf-8e80-d70ddcb28e58","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 458 first peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b5397d36-8664-4c55-96ee-542a55dc36b1","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 459 second peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b5397d36-8664-4c55-96ee-542a55dc36b1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 460 peer became unavailable
,ok 461 it was wifi peer
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b5397d36-8664-4c55-96ee-542a55dc36b1","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 we found peer again
,ok 463 it was wifi peer
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b5397d36-8664-4c55-96ee-542a55dc36b1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,ok 465 it was wifi peer
,# teardown
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"09fef3ab-62bc-49cf-8e80-d70ddcb28e58","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 466 error should be null
,ok 467 error should be null
,# setup
,ok 468 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 53381'
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"beceb149-10cc-48c5-9296-a6ef204e48fa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 first peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5741584-b084-4ffc-a45b-ce6ed8a2b108","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 473 second peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"beceb149-10cc-48c5-9296-a6ef204e48fa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 474 peer became unavailable
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c5741584-b084-4ffc-a45b-ce6ed8a2b108","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 475 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 476 error should be null
,ok 477 error should be null
,# setup
,ok 478 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 479 error should be null
,ok 480 error should be null
,# setup
,ok 481 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 482 error should be null
,ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aa0a221c-4e78-4ac1-8518-20ebb95957fe","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 485 peer discovered ,first time does not have new address
2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aa0a221c-4e78-4ac1-8518-20ebb95957fe","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 486 address has not been changed
2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aa0a221c-4e78-4ac1-8518-20ebb95957fe","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 487 new port handled correctly
2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aa0a221c-4e78-4ac1-8518-20ebb95957fe","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 488 new host handled correctly
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aa0a221c-4e78-4ac1-8518-20ebb95957fe","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 489 newAddressPort is null for unavailable peers
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-18 09:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 496 NOT IMPLEMENTED # SKIP
,# teardown
,ok 497 error should be null
,ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-18 09:54:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 500 error should be null
ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 503 should be equal
,# teardown
,ok 504 error should be null
,ok 505 error should be null
,# setup
,ok 506 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-18 09:54:28 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 contains expected properties
ok 511 the same hostAddress
ok 512 the same portNumber
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 516 contains expected properties
ok 517 the same hos,tAddress
ok 518 the same portNumber
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 519 error should be null
,ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'listening 53382'
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e693d67-9edd-40bc-aa7e-e2466430c5a5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 522 Got specific error message
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5e693d67-9edd-40bc-aa7e-e2466430c5a5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 523 error should be null
,ok 524 error should be null
,# setup
,ok 525 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'listening 53383'
,2017-07-18 09:54:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"64c50940-b92f-4586-a2b0-c0a9dc5f9e51","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:64c50940-b92f-4586-a2b0-c0a9dc5f9e51
,ok 526 native wrapper `disconnect` called once
,ok 527 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-18 09:54:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"64c50940-b92f-4586-a2b0-c0a9dc5f9e51","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 528 error should be null
,ok 529 error should be null
,# setup
,ok 530 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 531 error should be null
ok 532 error should be null
,# setup
,ok 533 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 534 error should be null
ok 535 error should be null
,# setup
,ok 536 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 537 error should be null
ok 538 error should be null
,# setup
,ok 539 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 540 error should be null
,ok 541 error should be null
,# setup
,ok 542 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 543 error should be null
,ok 544 error should be null
,# setup
,ok 545 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 546 error should be null
,ok 547 error should be null
,# setup
,ok 548 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 549 error should be null
ok 550 error should be null
,# setup
,ok 551 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'listening 53384'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F2FCF0B7-B629-4197-86AF-3921560081DD
,[ThaliCore] Browser.startListening
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2747b88c-b447-4dad-b879-8a1e3ba6bedf","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 552 Peer availabilities has one entry for our connection type
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"963ac7c4-b7c6-455d-b88f-7ff8ee28d0df","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 553 Peer availabilities has one entry for our connection type
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2747b88c-b447-4dad-b879-8a1e3ba6bedf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"963ac7c4-b7c6-455d-b88f-7ff8ee28d0df","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 554 No peers
,ok 555 No peers
,ok 556 No peers
,# teardown
,ok 557 error should be null
,ok 558 error should be null
,# setup
,ok 559 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'listening 53385'
2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b5341780-306e-4d77-8c1e-ad23add2a790","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 560 1
ok 561 2
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35aa9d11-9977-4dfb-8637-9c83f075bf79","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b5341780-306e-4d77-8c1e-ad23add2a790","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"35aa9d11-9977-4dfb-8637-9c83f075bf79","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 562 error should be null
,ok 563 error should be null
,# setup
,ok 564 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-18 09:54:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 565 error should be null
,ok 566 error should be null
,# setup
,ok 567 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'listening 53386'
ok 568 error should be null
ok 569 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45ABA631-FD53-4044-BA01-13,FE72BF09A5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:45ABA631-FD53-4044-BA01-13FE72BF09A5
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 570 error should be null
ok 571 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
[ThaliCore] Browser.startListening
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,ok 572 error should be null
ok 573 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}]'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}]'
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 50E8281F-8162-4C2A-8FC0-78964F5A9464 (syncValue: 0)'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
2017-07-18 09:54:34 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","generation":0}]'
2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","generation":0}'
[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> notConnected
[Thali,Core] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "50E8281F-8162-4C2A-8FC,0,-78964F5A9464", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier",:"104BF86E-803C-46C8-8A9E-8387091CD103","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:,syncValue:retryCount:completion:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
2017-07-18 09:54:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"104BF86E-803C-46C8-8A9E-,8387091CD103","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
2017-07-18 0,9:54:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","generation":0}]'
2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:34 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:50,E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,0E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}]'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"50E,8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generatio,n":0}]'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","generation":0}'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:54:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:54:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:50,E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,0E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-1,8 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A2FF3948-3AB1-4483-B3E0-379DCE76812F (syncValue: 1)'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", ge,neration: 0)
,[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unavailable","portNumber":null}'
2017-07-1,8 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 104BF8,6E-803C-46C8-8A9E-8387091CD103 (syncValue: 2)'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "10,4BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"generation":null,"portNum,ber":null,"recreated":true}'
2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09,:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A2FF3948-3AB1-4483-B3E0-379DCE76812F","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53396
2017-07-18 09:54:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":53396}'
,2017-07-18 09:54:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1329D84C-3DE0-4ED2-9740-36D47DF4B8A6 (syncValue: 3)'
,2017-07-18 09:54:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [3, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
[ThaliCore] Advertiser: session connected Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074 state: notConnected -> connecting
,2017-07-18 09:54:40 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:40 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
[ThaliCore] Advertiser: session connected Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53399
,2017-07-18 09:54:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":53399}'
,[ThaliCore] BrowserManager.disconnect peer:50E8281F-8162-4C2A-8FC0-78964F5A9464
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
,[ThaliCore] BrowserManager.disconnect peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [3, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
,[ThaliCore] Session.startOutputStream(with:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [3, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:54:43 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:43 - DEBUG testUtils: 'Got end'
,ok 574 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
,[ThaliCore] Session.session(_:peer:didChange:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
[ThaliCore] Session.startOutputStream(with:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,4 [3, 21, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:54:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"104BF86E-803C-46C8-8A9E-8387091CD103","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:45ABA631-FD53-4044-BA01-13FE72BF09A5
,2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-18 09:54:45 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 575 error should be null
ok 576 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [3, 21, 22, 24]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [3, 22, 24]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler dis,connecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [3, 22]
,# setup
,ok 577 ThaliMobile should be stopped
,# test for data corruption
,2017-07-18 09:54:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 578 error should be null
,ok 579 error should be null
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# setup
[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [3]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# #testThaliPeerAction - test getters
,ok 580 getPeerIdentifier
,ok 581 getConnectionType
,ok 582 getActionType
,ok 583 getActionState
,ok 584 getPskIdentity
,ok 585 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 586 initial state
,ok 587 after start
,2017-07-18 09:54:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 588 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 589 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-18 09:54:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 590 clean kill
,ok 591 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 592 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 593 forever agent should have it's own destroy method
,ok 594 agent's destroy should be called
,ok 595 agent's destroy should not be called again
,ok 596 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 597 Entry counter must be 1
,ok 598 Entry exists
,ok 599 Size must be 1
,ok 600 Entry counter must be 2
,ok 601 Entry exists
,ok 602 Size must be 2
,ok 603 Entry counter must be 1
,ok 604 Entry exists
,ok 605 Size must be 3
,ok 606 Entry counter must be 2
,ok 607 Entry exists
,ok 608 Size must be 4
,ok 609 Entry 1_1 should not be found
,ok 610 Entry 1_1 does not exist
,ok 611 Size must be 3
,ok 612 Entry 1_2 should not be found
,ok 613 Entry 1_2 does not exist
,ok 614 Size must be 2
,ok 615 should be equal
,ok 616 Entry 2_1 should not be found
,ok 617 Entry 2_2 should not be found
,ok 618 Entry 2_1 does not exist
,ok 619 Entry 2_2 does not exist
,ok 620 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 621 Size must be100
,ok 622 Entries between 20 and MAXSIZE + 20 should exist
,ok 623 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 624 Entries between 6 and MAXSIZE + 4 should exist
,ok 625 Size should be MAXSIZE
,ok 626 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 627 WAITING state entry should not be removed
,ok 628 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 629 Size should be MAXSIZE
,ok 630 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 631 Kill should be called once
,ok 632 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 633 is an agent
,ok 634 enqueue is fine
,ok 635 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 636 is an agent
,ok 637 first enqueue is fine
,ok 638 is an agent
,ok 639 second enqueue is fine
,ok 640 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 641 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 642 is an agent
,ok 643 good enqueue
,ok 644 Identity should match
,2017-07-18 09:54:54 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:54 - DEBUG testUtils: 'Got end'
,ok 645 Got expected response
,ok 646 Got psk call back
,# teardown
,2017-07-18 09:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 647 is an agent
,ok 648 enqueue worked
,ok 649 is an agent
,ok 650 enqueue 2 worked
,ok 651 enqueue is not available when stopped
,ok 652 start action is killed
,ok 653 killed action is still killed
,ok 654 enqueued action when stopped is killed
,ok 655 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 656 good start
,ok 657 good enqueue
,ok 658 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 659 null arg
ok 660 wrong arg type
ok 661 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 662 good enqueue
ok 663 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 664 good enqueue
ok 665 2nd good enqueue
ok 666 we are in the pool
,ok 667 We are out of the pool
ok 668 Action was killed
ok 669 The original kill was called too
ok 670 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 671 good enqueue
,ok 672 first kill
,ok 673 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 674 1st good enqueue
ok 675 2nd good enqueue
ok 676 1st action is in the pool
ok 677 2nd action is in the pool
ok 678 1st action is out of the pool
ok 679 2st action is out of the pool
,ok 680 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-18 09:54:57 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 681 Got right error
,ok 682 Start should not be called
,ok 683 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-18 09:54:57 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-18 09:54:57 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 684 Got right error
,ok 685 Start should not be called
,ok 686 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 687 Got null
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 688 is an agent
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 689 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 690 Got Null
,ok 691 Got another null
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 692 is an agent
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 693 is an agent
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 694 Action 1 killed at least once
,ok 695 Action 1 went first
,ok 696 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication, response with no error!'
,ok 697 should have gotten null
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 698 Should have stopped nicely
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 699 Still looking for null
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 700 Yup, another null
,ok 701 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 702 Null 1
,ok 703 (unnamed assert)
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 704 is an agent
,ok 705 Null 3
,ok 706 Replication not yet called
,ok 707 Notification 2 not yet called
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 708 is an agent
,ok 709 Notification went first
,ok 710 Notification 2 not called yet
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 711 is an agent
,ok 712 Notification finished
,ok 713 Replication finished
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 714 is an agent
,ok 715 First does not throw
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 716 is an agent
,ok 717 Second does not throw
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 718 is an agent
,ok 719 first ok
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 720 is an agent
,ok 721 second ok
,ok 722 third ok
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-18 09:55:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-18 09:55:02 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 723 peerIdentifier should match
,ok 724 generation should match
,ok 725 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 726 good beacon
,ok 727 good preAmble
,ok 728 public keys match!
,ok 729 must return null after successful call
,ok 730 Once start returns the action should be in KILLED state
,# teardown
,2017-07-18 09:55:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 731 Response should be HTTP_BAD_RESPONSE
,ok 732 must return null after successful call
,# teardown
,2017-07-18 09:55:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 733 Response should be NETWORK_PROBLEM
,ok 734 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-18 09:55:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 735 Resolution should be BAD_PEER
,ok 736 correct error message
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 737 Call start once
,ok 738 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 739 must return null after successful call.
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 740 Should be Killed
,ok 741 Start after killed
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 742 Should be KILLED
,ok 743 must return null after successful kill
,# teardown
,2017-07-18 09:55:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 744 Should be KILLED
ok 745 must return null after successful kill
,# teardown
,2017-07-18 09:55:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 746 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 747 must return null after successful call
,# teardown
,2017-07-18 09:55:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-18 09:55:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 748 Should be NETWORK_PROBLEM caused closing server socket
,ok 749 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 750 Should be NETWORK_PROBLEM caused closing client socket
ok 751 Should be Could not establish TCP connection
,# teardown
,2017-07-18 09:55:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 752 publicKeysToNotify cannot be null
,ok 753 ecdh for local device cannot be null
,ok 754 milliseconds cannot be less than 0
,ok 755 milliseconds cannot be 0
,ok 756 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 757 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 758 should be equal
,ok 759 should be equal
,ok 760 (unnamed assert)
,ok 761 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 762 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 763 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 764 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 765 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 766 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 767 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 768 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 769 should be equal
,ok 770 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 771 should be equal
,ok 772 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 773 right number of calls to address book
,ok 774 good preAmble
,ok 775 good unencryptedKeyId
,ok 776 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 777 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 778 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 779 Matching numbers
,ok 780 We have an entry!
,ok 781 keys match
,ok 782 secrets match
,ok 783 We have an entry!
ok 784 keys match
,ok 785 secrets match
,ok 786 We have an entry!
,ok 787 keys match
,ok 788 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 789 Streams have same length
,ok 790 matching size
,ok 791 keys match
,ok 792 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 793 should be equal
,ok 794 peerDictionalty contains 2 peers
,ok 795 bluetooth peer's notification has correct connection type
,ok 796 tcp peer's notification has correct connection type
,2017-07-18 09:55:20 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-18 09:55:20 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-18 09:55:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 797 notification peer dictionary contains exactly 1 peer
2017-07-18 09:55:21 - WARN thaliNotificationClient: 'peer is not available'
ok 798 notification peer dictionary does not contain any peers
,2017-07-18 09:55:21 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-18 09:55:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 799 entry exists
,ok 800 entry is resolved
,# teardown
,2017-07-18 09:55:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 801 Action should be KILLED
,ok 802 Peer state should be RESOLVED
,# teardown
,2017-07-18 09:55:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 803 hostAddress must match
,ok 804 portNumber must match
,ok 805 suggestedTCPTimeout must match
,ok 806 connectionType must match
,ok 807 peerIDs must match
,# teardown
,2017-07-18 09:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 808 Correct error
,# teardown
,2017-07-18 09:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 809 hostAddress must match
,ok 810 portNumber must match
,ok 811 suggestedTCPTimeout must match
,ok 812 connectionType must match
,ok 813 peerIds must match
,# teardown
,2017-07-18 09:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-18 09:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 815 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 816 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 817 action should be resolved with NETWORK_PROBLEM error
ok 818 correct number of requests
ok 819 correct number of failures
ok 820 correct final peer state
,# teardown
,2017-07-18 09:55:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-18 09:55:28 - WARN thaliNotificationClient: 'peer is not available'
2017-07-18 09:55:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 821 peerDictionary should become empty
,# teardown
,2017-07-18 09:55:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-18 09:55:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 822 failed with expected error
,ok 823 peer state should be RESOLVED
,# teardown
,2017-07-18 09:55:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-18 09:55:29 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 824 First action failed
,ok 825 second action killed
# teardown
,2017-07-18 09:55:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 826 secrets are equal
,ok 827 Public key matches with the server key
,ok 828 hostAddress must match
,ok 829 portNumber must match
,ok 830 suggestedTCPTimeout must match
,ok 831 connectionType must match
,# teardown
,2017-07-18 09:55:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 832 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 833 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 834 All entries should be expired after 1 second
# teardown
,2017-07-18 09:55:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 835 All keys need to be available in the cache
,ok 836 All entries should be expired after 1 second
# teardown
,2017-07-18 09:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 837 Size of the cache should be 2
ok 838 Cache doesn't contain dictionary1
,ok 839 Size of the cache should be 1
ok 840 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-18 09:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 841 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 842 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-18 09:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 843 StartUpdateAdvertisingAndListening should not be called
,ok 844 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 845 no error
,ok 846 should be 204
,# teardown
,2017-07-18 09:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 847 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-18 09:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 848 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-18 09:55:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 849 no error
,ok 850 should be 200
,ok 851 should be equal
,ok 852 should be equal
,ok 853 (unnamed assert)
,ok 854 no error
,ok 855 should be 204
,# teardown
,2017-07-18 09:55:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 856 error should be null
,ok 857 should be 204
,# teardown
,2017-07-18 09:55:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 858 should be 404
,# teardown
,2017-07-18 09:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 859 equal keys
ok 860 not equal connection type
ok 861 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-18 09:55:41 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 862 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 863 second cleared dictionary
,2017-07-18 09:55:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 864 First start and on called correctly
,ok 865 First stop and removeListener called correctly
,ok 866 first action kill called
,ok 867 second action kill called
,ok 868 first cleared dictionary
,ok 869 first cleared pool
,ok 870 second cleared dictionary
,ok 871 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 872 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-18 09:55:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 873 listener has been set
,ok 874 peer dictionary has expected number of entries
,ok 875 Dictionary and pool have same action
,ok 876 ads match
,ok 877 PouchDB matches
,ok 878 DB Names match
,ok 879 public keys match
,ok 880 peer dictionary has expected number of entries
,ok 881 Dictionary and pool have same action
,ok 882 ads match
,ok 883 PouchDB matches
,ok 884 DB Names match
,ok 885 public keys match
,2017-07-18 09:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 886 start called once
,ok 887 One entry left
,ok 888 Dictionary and pool have same action
,ok 889 Start never called
,ok 890 Kill called once
,ok 891 no entries left
,ok 892 Third action is dead
,ok 893 peer dictionary has expected number of entries
,ok 894 Dictionary and pool have same action
,ok 895 ads match
,ok 896 PouchDB matches
,ok 897 DB Names match
,ok 898 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-18 09:55:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-18 09:55:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:55:43 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-18 09:55:43 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 899 right error
,# teardown
,2017-07-18 09:55:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-18 09:55:44 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-18 09:55:44 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 900 right error
,# teardown
,2017-07-18 09:55:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 901 Got error as expected
,# teardown
,2017-07-18 09:55:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 902 Got error as expected
,# teardown
,2017-07-18 09:55:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-18 09:55:46 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-18 09:55:46 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 903 Got error as expected
,# teardown
,2017-07-18 09:55:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-18 09:55:49 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:55:49 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:55:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 904 should be equal
,ok 905 All tests passed!
,# teardown
,2017-07-18 09:55:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-18 09:55:54 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:55:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:55:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 906 should be equal
,ok 907 All tests passed!
,# teardown
,2017-07-18 09:55:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-18 09:55:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-18 09:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 908 action should be killed
ok 909 Error should be timed out
,ok 910 No doc found
,# teardown
,2017-07-18 09:56:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-18 09:56:02 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:56:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 911 should be equal
,2017-07-18 09:56:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-18 09:56:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 912 action should be killed
ok 913 Error should be timed out
,# teardown
,2017-07-18 09:56:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 914 socket hung up
,# teardown
,2017-07-18 09:56:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 915 same getPeerAdvertisesDataForUs
ok 916 Same pouchdB
ok 917 same localDbName
ok 918 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-18 09:56:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'listening 53529'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Browser.startListening
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5998E650-08FC-45D0-A270-46ABE636425B
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}]'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Advertiser: session connected Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537 state: notConnected -> connecting
2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:56:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CF,7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 4)'
2,017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
[ThaliCor,e] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Advertiser: session connected Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","generation":0}]'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","generation":0}'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53532
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":53532}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537 state: connecting -> connected
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 5)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":53532}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 6)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":53532}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 7)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":53532}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 8)'
2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [3, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [3, 25, 26]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [3, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [3, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [3, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [3, 25, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [3, 25, 26, 27, 28, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [3, 25, 26, 27, 28, 29, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [3, 25, 26, 27, 28, 29, 31, 32]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [3, 26, 27, 28, 29, 31, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [3, 27, 28, 29, 31, 32]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [3, 27, 28, 29, 32]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [3, 27, 28, 32]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [3, 28, 32]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [3, 28]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE,8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [3, 28, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [3, 28, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [3, 28, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [3, 28, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [3, 28, 33, 34, 35, 36, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,8 [3, 28, 33, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:peer:didChange:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,35
[ThaliCore] VirtualSocket.deinit vsID:35 [3, 28, 33, 34, 36, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [3, 28, 33, 34, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adv,ertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:13 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [3, 28, 33, 34, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,9 [3, 28, 33, 34, 37, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [3, 28, 33, 34, 37, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [3, 28, 33, 34, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [3, 28, 33, 34, 39, 40, 41]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [3, 28, 33, 34, 39, 40, 41, 42]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [3, 28, 33, 34, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [3, 28, 33, 34, 39, 40, 41, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [3, 28, 33, 34, 39, 40, 41, 42, 43, 44, 45]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:44 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,6 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 47]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 47, 48]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:13 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 47, 48]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 51]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 51, 52]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 51, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53564
2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":53564}'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 9)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":53564}'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 10)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":53564}'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 11)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":53564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 54, 55, 56]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [3, 28, 33, 34, 39, 40,, 41, 42, 43, 45, 46, 48, 50, 53, 54, 55, 56, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:56
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:56 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 54, 55, 57]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 54, 57]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:54 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 57]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [3, 28, 33, 34, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 58]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted s,ocket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore,] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [3, 28, 33, 39, 40, 41, 42, 43, 45, 46, 48, 50, 53, 58]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [3, 28, 33, 39, 40, 42, 43, 45, 46, 48, 50, 53, 58]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [3, 28, 33, 39, 40, 42, 45, 46, 48, 50, 53, 58]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [3, 28, 39, 40, 42, 45, 46, 48, 50, 53, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.sock,etDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [3, 28, 40, 42, 45, 46, 48, 50, 53, 58]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[Thali,Core] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [3, 28, 40, 42, 45, 46, 50, 53, 58]
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [3, 28, 40, 45, 46, 50, 53, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [3, 28, 40, 45, 46, 50, 53, 58, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [3, 28, 45, 46, 50, 53, 58, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDo,main Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] Virtu,alSocket.deinit vsID:46 [3, 28, 45, 50, 53, 58, 59]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [3, 28, 45, 50, 53, 58, 59, 60]
,[ThaliCore] VirtualSocket.deinit vsID:50 [3, 28, 45, 53, 58, 59, 60]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [3, 28, 45, 58, 59, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:58 [3, 28, 45, 59, 60]
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:59 [3, 28, 45, 60]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:60 [3, 28, 45]
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [3, 28, 45, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:17 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'Got error in update:  Stop Called, but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5998E650-08FC-45D0-A270-46ABE636425B
,2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:56:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-18 09:56:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:56:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 919 passed
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [3, 28, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'listening 53573'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
,[ThaliCore] Browser.startListening
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E9A60538-A18D-473B-B89F-8BF9C1999CE5
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
2017-07-18 09:56:19 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}]'
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 12)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":53532}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 13)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":53532}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 14)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":53532}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 15)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,2 [3, 28, 45, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E6017410,3537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [3, 28, 45, 62, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [3, 28, 45, 62, 63, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore,] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [3, 28, 45, 62, 63, 64, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] Advertise,rRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler, ,disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [3, 28, 45, 63, 64, 65]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] AdvertiserRelay.didCloseVirtual,SocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:65
,[ThaliCore] VirtualSocket.closeStreams() vsID:65
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:63
,[ThaliCore] VirtualSocket.deinit vsID:63 [3, 28, 45, 64, 65]
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":53532}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [3, 28, 45, 64, 65, 66]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [3, 28, 45, 64, 65, 66, 67]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:67
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
,[ThaliCore] VirtualSocket.deinit vsID:66 [3, 28, 45, 64, 65, 67]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:67
,[ThaliCore] VirtualSocket.deinit vsID:67 [3, 28, 45, 64, 65]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.d,idSocketDisconnectHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [3, 28, 45, 64, 65, 68]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [3, 28, 45, 64, 65, 68, 69]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:68
[ThaliCore] VirtualSocket.closeStreams() vsID:68
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:69
[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:69
[ThaliCore] VirtualSocket.deinit vsID:69 [3, 28, 45, 64, 65, 68]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [3, 28, 45, 64, 65, 68, 70]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:70
[ThaliCore] VirtualSocket.deinit vsID:70 [3, 28, 45, 64, 65, 68]
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 16)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":null,"portNumber":53532}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7,1 [3, 28, 45, 64, 65, 68, 71]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40,A1-994C-F57FF2477BE4:0
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 17)'
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17","error":null,"portNumber":53532}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 18)'
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) found active relay
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":53532}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [3, 28, 45, 64, 65, 68, 71, 72]
[ThaliCore] Browser.browser(_:foundPeer:withDiscove,ryInfo:) found peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for ,7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 19)'
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF,2477BE4", generation: 0) found active relay
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"19","error":null,"portNumber":53532}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socke,t error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerA,vailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","generation":0}]'
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailabl,e":true,"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","generation":0}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler dis,connecting:false
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:71
[ThaliCore] TCPListener.socket(_:didAcceptN,ewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.closeStreams() vsID:71
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] Session.startOutputStream(with:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnectin,g:false
[ThaliCore] VirtualSocket exited RunLoop vsID:71
[ThaliCore] VirtualSocket.deinit vsID:71 [3, 28, 45, 64, 65, 68, 72]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [3, 28, 45, 64, 65, 68, 72, 73]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:74 [3, 28, 45, 64, 65, 68, 72, 73, 74]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:75 [3, 28, 45, 64, 65, 68, 72, 73, 74, 75]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 20)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A,711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:73
[ThaliCore] VirtualSocket.closeStreams() vsID:73
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:73
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:73 [3, 28, 45, 64, 65, 68, 72, 74, 75]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:74
[ThaliCore] VirtualSocket.closeStreams() vsID:74
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited Ru,nLoop vsID:74
[ThaliCore] VirtualSocket.deinit vsID:74 [3, 28, 45, 64, 65, 68, 72, 75]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:75
[ThaliCore] VirtualSocket.closeStreams() vsID:75
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:75
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:75 [3, 28, 45, 64, 65, 68, 72]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:76 [3, 28, 45, 64, 65, 68, 72, 76]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[T,haliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:77 [3, 28, 45, 64, 65, 68, 72, 76, 77]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7,8 [3, 28, 45, 64, 65, 68, 72, 76, 77, 78]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:79 [3, 28, 45, 64, 65, 68, 72, 76, 77, 78, 79]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:76
[ThaliCore] VirtualSocket.closeStreams() vsID:76
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSL,ocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChan,ged event from native layer [{"peerAvailable":true,"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","generation":0}]'
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:77
[ThaliCore] VirtualSocket.closeStreams() vs,ID:77
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","generation":0}'
[ThaliCore] VirtualSocket exited RunLoop vsID:76
[T,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
haliCore] VirtualSocket.deinit vsID:76 [3, 28, 45, 64, 65, 68, 72, 77, 78, 79]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:78
[ThaliCore] VirtualSocket.closeStreams() vsID:78
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:79
[ThaliCore] VirtualSocket exited RunLoop vsID:77
[ThaliCore] Virtua,lSocket.closeStreams() vsID:79
[ThaliCore] VirtualSocket.closeStreams() vsID:79
[ThaliCore] VirtualSocket.deinit vsID:77 [3, 28, 45, 64, 65, 68, 72, 78, 79]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,0 [3, 28, 45, 64, 65, 68, 72, 78, 79, 80]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:80
[ThaliCore] VirtualSocket.closeStreams() vsID:80
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:80
[ThaliCore] VirtualSocket.deinit vsID:80 [3, 28, 45, 64, 65, 68, 72, 78, 79]
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53532
[ThaliCore] VirtualSocket.closeStreams() vsID:72
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDiscon,nectHandler
[ThaliCore] Session.disconnect() peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] TCPListener.deinit
[ThaliCore] VirtualSocket exited RunLoop vsID:72
[ThaliCore] Session.deinit peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore], VirtualSocket.deinit vsID:72 [3, 28, 45, 64, 65, 68, 78, 79]
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) relay removed
[ThaliCore] Session.init(session:identifier:connected:notConnect,ed:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Advertiser: session connected Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:),
[ThaliCore] Session.session(_:peer:didChange:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD state: notConnected -> connecting
,2017-07-18 09:56:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}]'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","generation":0}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:56:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:22 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:81 [3, 28, 45, 64, 65, 68, 78, 79, 81]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo,={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket v,sID:81
[ThaliCore] VirtualSocket.closeStreams() vsID:81
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:81
[ThaliCore] VirtualSocket.deinit vsID:81 [3, 28, 45, 64, 65, 68,, 78, 79]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53596
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20","error":null,"portNumber":53596}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 21)'
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) found active relay
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"21","error":null,"portNumber":53596}'
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 22)'
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) found active relay
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"22","error":null,"portNumber":53596}'
,2017-07-18 09:56:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4A711876-4C8F-4060-B5CA-D8ECB659AFA8 (syncValue: 23)'
2017-07-18 09:56:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0) found active relay
2017-07-18 09:56:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"23","error":null,"portNumber":53596}'
2,017-07-18 09:56:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 24)'
2017-07-18 09:56:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] TCPListener.socket(_:d,idAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtua,lSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with,:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:82 [3, 28, 45, 64, 65, 68, 78, 79, 82],
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:83 [3, 28, 45, 64, 65, 68,, 78, 79, 82, 83]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:84 [3, ,28, 45, 64, 65, 68, 78, 79, 82, 83, 84]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:85 [3, 28, 45, 64, 65, 68, 78, 79, 82, 83, 84, 85]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Advertiser: session connected Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:82
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:82
[ThaliCore] VirtualSocket.deinit vsID:82 [3, 28, 45, 64, 65, 68, 78, 79, 83, 84, 85]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:84
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:84
,[ThaliCore] VirtualSocket.deinit vsID:84 [3, 28, 45, 64, 65, 68, 78, 79, 83, 85]
,[ThaliCore] Session.session(_:peer:didChange:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:85
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:85
[ThaliCore] VirtualSocket.deinit vsID:85 [3, 28, 45, 64, 65, 68, 78, 79, 83]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:83
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:83
[ThaliCore] VirtualSocket.deinit vsID:83 [3, 28, 45, 64, 65, 68, 78, 79]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:86 [3, 28, 45, 64, 65, 68, 78, 79, 86]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-18 09:56:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 920 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:86
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:86
[ThaliCore] VirtualSocket.deinit vsID:86 [3, 28, 45, 64, 65, 68, 78, 79]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
,[ThaliCore] Session.session(_:peer:didChange:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,7 [3, 28, 45, 64, 65, 68, 78, 79, 87]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:88 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,9 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88, 89]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:89
[ThaliCore] VirtualSocket.closeStreams() vsID:89
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:89
[ThaliCore] VirtualSocket.deinit vsID:89 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:90 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88, 90]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NSLocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error, in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:90
[ThaliCore] VirtualSocket.closeStreams() vsID:90
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:90
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.deinit vsID:90 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88]
[ThaliCore] Session.,startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:91 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88, 91]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:92 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88, 91, 92]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,3 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88, 91, 92, 93]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:91
[ThaliCore] VirtualSocket.closeStreams() vsID:91
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket exited RunLoop vsID:91
,[ThaliCore] VirtualSocket.deinit vsID:91 [3, 28, 45, 64, 65, 68, 78, 79, 87, 88, 92, 93]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:88
[ThaliCore] VirtualSocket.closeStreams() vsID:88
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:88
[ThaliCore] VirtualSocket.deinit vsID:88 [3, 28, 45, 64, 65, 68, 78, 79, 87, 92, 93]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:92
,[ThaliCore] VirtualSocket.closeStreams() vsID:92
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:87
[ThaliCore] VirtualSocket.closeStreams() vsID:87
[ThaliCore] AdvertiserRelay.didCloseVirtualSoc,ketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:92
,[ThaliCore] VirtualSocket.deinit vsID:92 [3, 28, 45, 64, 65, 68, 78, 79, 87, 93]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:87
,[ThaliCore] VirtualSocket.deinit vsID:87 [3, 28, 45, 64, 65, 68, 78, 79, 93]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:94 [3, 28, 45, 64, 65, 68, 78, 79, 93, 94]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF state: connecting -> connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:93
[ThaliCore] VirtualSocket.closeStreams() vsID:93
,[ThaliCore] Session.session(_:peer:didChange:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53612
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:93
[ThaliCore] VirtualSocket.deinit vsID:93 [3, 28, 45, 64, 65, 68, 78, 79, 94]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDis,connect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"24","error":null,"portNumber":53612}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 25)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) found active relay
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"25","error":null,"portNumber":53612}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 26)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) found active relay
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"26","error":null,"portNumber":53612}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 27)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) found active relay
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"27","error":null,"portNumber":53612}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:95 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:96 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:97 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 97]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,8 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 97, 98]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:99 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 97, 98, 99]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:97
[ThaliCore] VirtualSocket.closeStreams() vsID:97
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:99
[ThaliCore] VirtualSocket.closeStreams() vsID:99
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:98
[ThaliCore] VirtualSocket.closeStreams() vsID:98
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:97
[ThaliCore] VirtualSocket.deinit vsID:97 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 98, 99]
[ThaliCore] VirtualSocket exited RunLoop vsID:99
,[ThaliCore] VirtualSocket.deinit vsID:99 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 98]
,[ThaliCore] VirtualSocket exited RunLoop vsID:98
[ThaliCore] VirtualSocket.deinit vsID:98 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:100 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:101 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 101]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:102 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 101, 102]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:101
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:101
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:101
,[ThaliCore] VirtualSocket.deinit vsID:101 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 102]
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 28)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 29)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"29","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7CF7E90F-A14F-40A1-994C-F57FF2477BE4 (syncValue: 30)'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"30","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:103 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 102, 103]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:103
[ThaliCore] VirtualSocket.closeStreams() vsID:103
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:103
,[ThaliCore] VirtualSocket.deinit vsID:103 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 102]
,2017-07-18 09:56:27 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-18 09:56:27 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-18 09:56:27 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:104 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 102, 104]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:105 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 102, 104, 105]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:106 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 102, 104, 105, 106]
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:107 [3, 28, 45, 64, 65, 68, 78, 79, 94, 95, 96, 100, 102, 104, 105, 106, 107]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CF7E90F-A14F-40A1-994C-F57FF2477BE4","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
,[ThaliCore] BrowserManager.disconnect peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
,[ThaliCore] BrowserManager.disconnect peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:95
[ThaliCore] VirtualSocket.closeStreams() vsID:95
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:95
[ThaliCore] VirtualSocket.deinit vsID:95 [3, 28, 45, 64, 65, 68, 78, 79, 94, 96, 100, 102, 104, 105, 106, 107]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:96
[ThaliCore] VirtualSocket.closeStreams() vsID:96
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:96
,[ThaliCore] VirtualSocket.deinit vsID:96 [3, 28, 45, 64, 65, 68, 78, 79, 94, 100, 102, 104, 105, 106, 107]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:104
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:104
[ThaliCore] VirtualSocket.deinit vsID:104 [3, 28, 45, 64, 65, 68, 78, 79, 94, 100, 102, 105, 106, 107]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:100
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:100
[ThaliCore] BrowserRelay.didSocketDisconnectHa,ndler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:105
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:100
[ThaliCore] VirtualSocket.deinit vsID:100 [3, 28, 45, 64, 65, 68, 78, 79, 94, 102, 105, 106, 107]
[ThaliCore] VirtualSocket exited RunLoop vsID:105
[ThaliCore] VirtualSocket.deinit vsID:105 [3, 28, 45, 6,4, 65, 68, 78, 79, 94, 102, 106, 107]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:94
[ThaliCore] VirtualSocket.closeStreams() vsID:94
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:106
[ThaliCore] Adver,tiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:94
[ThaliCore] VirtualSocket.deinit vsID:94 [3, 28, 45, 64, 65, 68, 78, 79, 102, 106, 107]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:106
[ThaliCore] VirtualSocket.deinit vsID:106 [3, 28, 45, 64, 65, 68, 78, 79, 102, 107]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:102
[ThaliCore] VirtualSocket.closeStreams() vsID:102
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:102
[ThaliCore] VirtualSocket.deinit vsID:102 [3, 28, 45, 64, 65, 68, 78, 79, 107]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDid,Disconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:107
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:107
,[ThaliCore] VirtualSocket.deinit vsID:107 [3, 28, 45, 64, 65, 68, 78, 79]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Session.startOutputStream(with:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:108 [3, 28, 45, 64, 65, 68, 78, 79, 108]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:109 [3, 28, 45, 64, 65, 68, 78, 79, 108, 109]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:110 [3, 28, 45, 64, 65, 68, 78, 79, 108, 109, 110]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:110
,[ThaliCore] VirtualSocket.closeStreams() vsID:110
,[ThaliCore] VirtualSocket exited RunLoop vsID:110
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:110 [3, 28, 45, 64, 65, 68, 78, 79, 108, 109]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:111 [3, 28, 45, 64, 65, 68, 78, 79, 108, 109, 111]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:111
,[ThaliCore] VirtualSocket.closeStreams() vsID:111
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:111
,[ThaliCore] VirtualSocket.deinit vsID:111 [3, 28, 45, 64, 65, 68, 78, 79, 108, 109]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] Session.startOutputStream(with:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:112 [3, 28, 45, 64, 65, 68, 78, 79, 108, 109, 112]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:112
[ThaliCore] VirtualSocket.closeStreams() vsID:112
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:112
,[ThaliCore] VirtualSocket.deinit vsID:112 [3, 28, 45, 64, 65, 68, 78, 79, 108, 109]
,2017-07-18 09:56:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-18 09:56:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 921 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:109
,[ThaliCore] VirtualSocket exited RunLoop vsID:109
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:109 [3, 28, 45, 64, 65, 68, 78, 79, 108]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:108
[ThaliCore] VirtualSocket.closeStreams() vsID:108
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:108
[ThaliCore] VirtualSocket.deinit vsID:108 [3, 28, 45, 64, 65, 68, 78, 79]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E9A60538-A18D-473B-B89F-8BF9C1999CE5
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4A711876-4C8F-4060-B5CA-D8ECB659AFA8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:68
[ThaliCore] VirtualSocket.deinit vsID:68 [3, 28, 45, 64, 65, 78, 79]
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:56:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 922 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 923 should throw
,ok 924 should throw
,ok 925 (unnamed assert)
,ok 926 (unnamed assert)
,ok 927 (unnamed assert)
,ok 928 (unnamed assert)
,ok 929 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 930 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 931 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 932 should be equal
,# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 933 should be equal
,ok 934 should be equal
,ok 935 should throw
,# teardown
,# setup
,# Test TransientState
,ok 936 should throw
,ok 937 should throw
,ok 938 should be equal
,ok 939 should be equal
,ok 940 should be equal
,ok 941 should be equal
,ok 942 (unnamed assert)
,ok 943 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 944 verify failed
,ok 945 constructor called once
,ok 946 constructor called with right args
,ok 947 match start arg
,ok 948 start called once
,ok 949 stop called once
,ok 950 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-07-18 09:56:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 951 verify failed
,ok 952 constructor called once
,ok 953 constructor called with right args
,ok 954 match start arg
,ok 955 start called once
,ok 956 stop called once
,ok 957 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-07-18 09:56:34 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 958 verify failed
,ok 959 constructor called once
,ok 960 constructor called with right args
,ok 961 match start arg
,ok 962 start called once
,ok 963 stop called once
,ok 964 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-18 09:56:35 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 965 verify failed
,ok 966 constructor called once
,ok 967 constructor called with right args
,ok 968 match start arg
,ok 969 start called once
,ok 970 stop called once
,ok 971 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-18 09:56:36 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 972 verify failed
ok 973 constructor called once
,ok 974 constructor called with right args
,ok 975 match start arg
,ok 976 start called once
,ok 977 stop called once
,ok 978 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-18 09:56:36 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 979 verify failed
,ok 980 constructor called once
,ok 981 constructor called with right args
,ok 982 match start arg
,ok 983 start called once
,ok 984 stop called once
,ok 985 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 986 verify failed
,ok 987 constructor called once
,ok 988 constructor called with right args
,ok 989 match start arg
,ok 990 start called once
,ok 991 stop called once
,ok 992 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 993 verify failed
,ok 994 constructor called once
,ok 995 constructor called with right args
,ok 996 last start before stop
,ok 997 empty first start
,ok 998 full second start
,ok 999 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 1000 verify failed
ok 1001 constructor called once
ok 1002 constructor called with right args
,ok 1003 start before stop
ok 1004 We got at least 3 calls to start
ok 1005 at least 3
ok 1006 default 1
ok 1007 1 run
ok 1008 default 2
ok 1009 2 run
ok 1010 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 1011 start out null
,2017-07-18 09:56:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1012 back to null
,2017-07-18 09:56:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1013 still null
,ok 1014 verify failed
,ok 1015 constructor called once
,ok 1016 constructor called with right args
,ok 1017 first start before first stop
,ok 1018 first stop before second start
,ok 1019 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-18 09:56:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1020 verify failed
,ok 1021 constructor called once
,ok 1022 constructor called with right args
,ok 1023 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-18 09:56:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1024 verify failed
,ok 1025 constructor called once
,ok 1026 constructor called with right args
,ok 1027 (unnamed assert)
,ok 1028 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-18 09:56:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1029 verify failed
ok 1030 constructor called once
,ok 1031 constructor called with right args
,ok 1032 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-18 09:56:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1033 verify failed
,ok 1034 constructor called once
,ok 1035 constructor called with right args
,ok 1036 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 1037 should be equal
,ok 1038 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:56:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 1039 Got right error
,# teardown
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-18 09:56:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 1040 Got socket hang up
,# teardown
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-18 09:56:43 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 1041 Got 500 as expected
,# teardown
,2017-07-18 09:56:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 1042 should be equal
,ok 1043 revs are equal
,# teardown
,2017-07-18 09:56:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 1044 should be equal
,ok 1045 revs are equal
,# teardown
,2017-07-18 09:56:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 1046 should be equal
,ok 1047 revs are equal
,ok 1048 should be equal
,ok 1049 revs are equal
,ok 1050 should be equal
,ok 1051 revs are equal
,# teardown
,2017-07-18 09:56:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/F,9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/F9B239D5-,7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-18 09:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1052 Our rev is old so we should fail
,# teardown
,2017-07-18 09:56:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1053 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/F,9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/F9B239D5-,7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-18 09:56:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-18 09:56:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1054 stop caused us to fail
,ok 1055 We specifically failed on a stop before put
,# teardown
,2017-07-18 09:56:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1056 failed due to stop
,ok 1057 failed due to stop
,# teardown
,2017-07-18 09:56:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1058 should be equal
,# teardown
,2017-07-18 09:56:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-18 09:56:57 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1059 Expected bad seq error
,# teardown
,2017-07-18 09:56:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1060 Different promises
,ok 1061 Timer was cancelled
,ok 1062 should be equal
,# teardown
,2017-07-18 09:57:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1063 One go and one blocked
,ok 1064 All blocked
,ok 1065 Still blocked
,ok 1066 should be equal
,# teardown
,2017-07-18 09:57:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1067 We waited long enough
,ok 1068 should be equal
,# teardown
,2017-07-18 09:57:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1069 Should have gotten same timer promise
,ok 1070 Still same timer promise
,ok 1071 We waited long enough
,ok 1072 should be equal
,# teardown
,2017-07-18 09:57:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-18 09:57:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1073 expressPouchDB was called once
,ok 1074 expressPouchDB was called with 2 arguments
,ok 1075 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1076 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1077 PouchDB was called once
,ok 1078 PouchDB was called with 1 arguments
,ok 1079 PouchDB was called with 'dbName' as 1-st argument
,ok 1080 ThaliSendNotificationBasedOnReplication was called once
,ok 1081 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1082 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1083 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1084 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1085 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1086 ThaliPullReplicationFromNotification was called once
,ok 1087 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1088 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1089 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1090 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1091 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1092 Salti was called once
,ok 1093 Salti was called with 4 arguments
,ok 1094 Salti was called with 'dbName' as 1-st argument
,ok 1095 Salti was called with 'acl' as 2-st argument
,ok 1096 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1097 Salti was called with 'options' as 4-st argument
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:09 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'listening 53700'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:37BF9DDC-10BE-40BF-9EB5-EE1E1474C8CD
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A79397D5-A48E-4505-8FBA-E09F408DA79B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A79397D5-A48E-4505-8FBA-E09F408DA79B
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1098 ThaliMobile.start was called once
,ok 1099 ThaliMobile.start was called with 3 arguments
,ok 1100 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1101 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1102 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1103 ThaliMobile.startListeningForAdvertisements was called once
,ok 1104 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1105 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1106 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1107 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1108 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1110 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1111 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1112 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:09 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A79397D5-A48E-4505-8FBA-E09F408DA79B
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1113 ThaliMobile.stop was called once
,ok 1114 ThaliMobile.stop was called with 0 arguments
,ok 1115 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1116 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1117 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1118 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1119 expressPouchDB was called once
,ok 1120 expressPouchDB was called with 2 arguments
,ok 1121 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1122 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1123 PouchDB was called once
,ok 1124 PouchDB was called with 1 arguments
,ok 1125 PouchDB was called with 'dbName' as 1-st argument
,ok 1126 ThaliSendNotificationBasedOnReplication was called once
,ok 1127 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1128 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1129 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1130 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1131 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1132 ThaliPullReplicationFromNotification was called once
,ok 1133 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1134 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1135 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1136 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1137 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1138 Salti was called once
,ok 1139 Salti was called with 4 arguments
,ok 1140 Salti was called with 'dbName' as 1-st argument
,ok 1141 Salti was called with 'acl' as 2-st argument
,ok 1142 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1143 Salti was called with 'options' as 4-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53702'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:87151D57-7FB5-4F02-8647-C559DCAB85B4
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BC2F11B5-6DE7-429C-BD3D-36BDA42A82FC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BC2F11B5-6DE7-429C-BD3D-36BDA42A82FC
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1144 ThaliMobile.start was called once
,ok 1145 ThaliMobile.start was called with 3 arguments
,ok 1146 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1147 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1148 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1149 ThaliMobile.startListeningForAdvertisements was called once
,ok 1150 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1151 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1152 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1153 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1154 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1155 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1156 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1157 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1158 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:BC2F11B5-6DE7-429C-BD3D-36BDA42A82FC
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1159 ThaliMobile.stop was called once
,ok 1160 ThaliMobile.stop was called with 0 arguments
,ok 1161 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1162 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1163 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1164 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53704'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:92FD7B3A-DD04-48A2-A2A5-82255B0BA511
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3D18B42E-9E61-498B-B6CC-699C4A75873C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3D18B42E-9E61-498B-B6CC-699C4A75873C
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3D18B42E-9E61-498B-B6CC-699C4A75873C
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53706'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FFF920D3-4A30-42A3-97F9-93067D44CA17
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A54B646F-B13D-4237-8828-D0C0B5E77543", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A54B646F-B13D-4237-8828-D0C0B5E77543
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A54B646F-B13D-4237-8828-D0C0B5E77543
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53708'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4AD7041F-229A-4AE3-876A-C604FC4D8AB3
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7ACF4B9F-B0C0-49D5-92B6-C6BDD4EC8332", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7ACF4B9F-B0C0-49D5-92B6-C6BDD4EC8332
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1165 ThaliMobile.start was called once
,ok 1166 ThaliMobile.start was called with 3 arguments
,ok 1167 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1168 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1169 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1170 ThaliMobile.startListeningForAdvertisements was called once
,ok 1171 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1172 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1173 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1174 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1175 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1176 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1177 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1178 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1179 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7ACF4B9F-B0C0-49D5-92B6-C6BDD4EC8332
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test write
,2017-07-18 09:57:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'test write''
,# teardown
,# setup
,# test repeat write 1
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER res,ult: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is, not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after pe,er listener recreation'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers pres,ented then `discoveryDOS` event should be emitted'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOG,GER result: passed - can get data from all participants'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test write'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:279:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-,3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expo,rts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/Ap,plication/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/,node_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07,-18 09:57:11 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-18 10:00:11 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/c,ontainers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/ww,w,/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/F9B239D5-7FB7-4499-BFEE-3B8914FBC48E/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-18 10:00:11 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
