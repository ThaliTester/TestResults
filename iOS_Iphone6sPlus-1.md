#### Test 113351851151165c_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9E2F4328-C422-456C-8D02-CB5F305B1384/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/9E2F4328-C422-456C-8D02-CB5F305B1384/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851151165c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65531"
,(lldb)     command script import "/tmp/9E2F4328-C422-456C-8D02-CB5F305B1384/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-18 09:48:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:48:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:48:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:48:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:48:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:48:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:48:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "073B5C77-3644-407B-B587-9CAC571C2DE2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:073B5C77-3644-407B-B587-9CAC571C2DE2
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AADB2143-8848-4A61-B9D5-31F1A6B144A3
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1C2D8BB2-EE7E-4FF9-8713-B44B8ED3D79D
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A7B401B9-FD6E-4E68-B9FB-578DB2E8B9DD", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:A7B401B9-FD6E-4E68-B9FB-578DB2E8B9DD
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7B401B9-FD6E-4E68-B9FB-578DB2E8B9DD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B401B9-FD6E-4E68-B9FB-578DB2E8B9DD", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-18 09:48:46 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.582791090011597
,2017-07-18 09:48:46 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-18 09:48:46 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A7B401B9-FD6E-4E68-B9FB-578DB2E8B9DD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A7B401B9-FD6E-4E68-B9FB-578DB2E8B9DD", generation: 0)
,2017-07-18 09:48:47 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-18 09:48:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-18 09:48:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-18 09:48:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-18 09:48:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-18 09:48:49 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-18 09:48:49 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-18 09:48:49 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-18 09:50:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-18 09:50:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-18 09:50:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-18 09:51:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 5 should be equal
ok 6 should be equal
,# teardown
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
,2017-07-18 09:51:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:51:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-18 09:51:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:51:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B0E139D2-52EE-44D2-9350-B9AE5F6AFA46
[ThaliCore] Browser.startListening
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:51:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:51:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2B74F06-0C4C-473D-804E-2AE193EE9BB5
[ThaliCore] Browser.startListening
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:51:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-18 09:51:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18, 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:17 - DEBUG thal,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:51:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:51:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:51:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8EC24313-BF00-4E59-B786-F99D7828D6FF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8EC24313-BF00-4E59-B786-F99D7828D6FF
,2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8EC24313-BF00-4E59-B786-F99D7828D6FF
2017-07-18 09:51:19 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2083B837-8657-4E28-94E7-17FF1F33B74A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2083B837-8657-4E28-94E7-17FF1F33B74A
2017-07-18 0,9:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHa,ndler:) Peer(uuid: "2083B837-8657-4E28-94E7-17FF1F33B74A", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:2083B837-8657-4E28-94E7-17FF1F33B74A
2017-07-18 09:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening twic,e without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:20 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:5,1:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertisin,g() peerID:2083B837-8657-4E28-94E7-17FF1F33B74A
[ThaliCore] Advertiser.stopAdvertising() peerID:2083B837-8657-4E28-94E7-17FF1F33B74A
,2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd,vertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:51:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:51:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ADD621AC-46A0-4CE2-9B2B-724F599DC244", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ADD621AC-46A0-4CE2-9B2B-724F599DC244
2017-07-18 0,9:51:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:51:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:642B1CBC-43F7-43A5-A80A-0F43576A9F4B
[ThaliCore] Browser.startListening
2017-07-18 09:51:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-18 09:51:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80D74A42-61EC-45BE-AA90-5C1DF610E490:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80D74A42-61EC-45BE-AA90-5C1DF610E490", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2901452-AE22-4CB3-96E1-1C614499BC0E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2901452-AE22-4CB3-96E1-1C614499BC0E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADD621AC-46A0-4CE2-9B2B-724F599DC244:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD621AC-46A0-4CE2-9B2B-724F599DC244", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 ,09:51:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:ADD621AC-46A0-4CE2-9B2B-724F599DC244
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd,vertisingStateUpdateNonTCP registered to native'
2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:60D5D6A0-54FF-41BD-9405-55F97D5EB615
2017-07-18 0,9:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:78520665-8F5D-47F2-B15B-379A15DC8B71
[Thal,i,Core] Browser.startListening
2017-07-18 09:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:51:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:39 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E7823D58-1DBC-4490-B24C-D54ABF468217","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E7823D58-1DBC-4490-B24C-D54ABF468217 (syncValue: x0skO03slZijc7MPQWQEkGMzThUr8h98)'
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5F321996-1BF0-489C-8C70-3A82EC46FE51","generation":0}'
2017-07-18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,18 09:51:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60D5D6A0-54FF-41BD-9405-55F97D5EB615:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27
[ThaliCore] Advertiser: session connected Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27
,[ThaliCore] Session.session(_:peer:didChange:) peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0 state: connecting -> connected
[ThaliCore] ,Browser: session connected to Peer(uuid: "E7823D58-1DBC-4490-B24C-D54ABF468217", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52552
2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"x0skO03slZijc7MPQWQEkGMzThUr8h98","error":null,"portN,umber":52552}'
2017-07-18 09:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'x0skO03slZijc7MPQWQEkGMzThUr8h98', error: 'null', listeningPort: '52552''
,2017-07-18 09:51:44 - INFO testThaliMobileNative: ''
ok 97 Must have listeningPort
ok 98 listeningPort must be a number
ok 99 listening port should not be 0
,# teardown
,2017-07-18 09:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:60D5D6A0-54FF-41BD-9405-55F97D5EB615
2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,o,nTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] B,rowserManager.disconnect peer:E7823D58-1DBC-4490-B24C-D54ABF468217
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52552
[ThaliCore] Session.disconnect() peer:E7823D58-,1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "60D5D6A0-54FF-41BD-9405-55F97D5EB615", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:E7823D58-1DBC-4490-B24C-D54ABF468217:0
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:E506D4DB-CEEA-4D18-8C6A-D0A712DE0D27
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:31978CED-B0AE-4798-B7C8-849267BE9E39
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EB6D9739-6FDA-4FE1-B84C-21471DC,A71A1
[ThaliCore] Browser.startListening
2017-07-18 09:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:51:46 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:46 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5F321996-1BF0-489C-8C70-3A82EC46FE51","generation":0}'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5F321996-1BF0-489C-8C70-3A82EC46FE51 (syncValue: 6EKhlIHmkmKCY7Z77ctxiGPa7rO5Jq1o)'
,2017-07-18 09:51:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
2017-07-18 09:51:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","generation":0}'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:47 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", g,eneration: 0)
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A0499C8-21DB-4F11-B792-A89F6B7556D1","generation":0}'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31978CED-B0AE-4798-B7C8-849267BE9E39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31978CED-B0AE-4798-B7C8-849267BE9E39", generation: 0)
est!'
2017-07-18 09:51:47 - ,DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F,321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5F321996-1BF0-489C-8C70-3A82EC46FE51", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5F321996,-1BF0-489C-8C70-3A82EC46FE51 error: max retries exceeded
2017-07-18 09:51:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6EKhlIHmkmKCY7Z77ctxiGPa7rO5Jq1o","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:51:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6EKhlIHmkmKCY7Z77ctxiGPa7rO5Jq1o', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:51:50 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"5F321996-1BF0-489C-8C70-3A82EC46FE51","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:51:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:51:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5F321996-1BF0-489C-8C70-3A82EC46FE51","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:51:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:51:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:51:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85ED1FFD-D50E-497A-9762-800969B8B575 (syncValue: WVzgSCO,gaz9aTnC2euTohNn0svW6VUzu)'
2017-07-18 09:51:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85ED1FFD-D50E,-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:51:50 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-18 09:51:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5F321996-1BF0-489C-8C70-3A82EC46FE51:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52561
2017-07-18 09:51:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WVzgSCOgaz9aTnC2euTohNn0svW6VUzu",,"error":null,"portNumber":52561}'
2017-07-18 09:51:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WVzgSCOgaz9aTnC2euTohNn0svW6VUzu', error: 'null', listeningPort: '52561''
,Connecting to the localhost:52561
,Connected to the localhost:52561
2017-07-18 09:51:52 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-18 09:51:52 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:1
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-07-18 09:51:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:31978CED-B0AE-4798-B7C8-849267BE9E39
2017-07-18 09:51:56 - DEBUG thaliMobileNativeWr,apper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:51:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisi,ngAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:85ED1FFD-D50E-497A-9762-800969B8B575
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52561
[Thali,Core] Session.disconnect() peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:51:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:51:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:13A16B2D-9A9A-4856-BD41-17E83D3985F1
2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:51:57, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4F7924C0-B17C-4DB1-B567-85D55AC0A797
[ThaliCore] Browser.startList,ening
2017-07-18 09:51:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:51:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tr,ue}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:51:57 - INFO thaliMobile: 'Filtered out discoveryAdvertis,ingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B5,75","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85ED1FFD-D50E-497A-9762-800969B8B575 (syncValue: qljXkfPzt6CHKzaH3x2YLF3r1xmABgwX)'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A0499C8-21DB-4F11-B792-A89F6B7556D1","generation":0}'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1A0499C8-21DB-4F11-B792-A89F6B7556D1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1A0499C8-21DB-4F11-B792-A89F6B7556D1", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:13A16B2D-9A9A-4856-BD41-17E83D3985F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
2017-07-18 09:51:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2B7CA6F7-3F9F-4284-8D14-32237A26476F","generation":0}'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:58 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", g,eneration: 0)
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15","generation":0}'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running ,test!'
,2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85,ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,5ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85,ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:85ED1FFD,-D50E-497A-9762-800969B8B575 error: max retries exceeded
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qljXkfPzt6CHKzaH3x2YLF3r1xmABgwX","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qljXkfPzt6CHKzaH3x2YLF3r1xmABgwX', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2B7CA6F7-3F9F-4284-8D14-32237A26476F (syncValue: V9elEdQ,JCuWpD2jtsiCH1gfbEn69fHfz)'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B7CA6F7-3F9F,-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-18 09:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] Advertiser: session connected Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52578
2017-07-18 09:52:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"V9elEdQJCuWpD2jtsiCH1gfbEn69fHfz",,"error":null,"portNumber":52578}'
2017-07-18 09:52:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'V9elEdQJCuWpD2jtsiCH1gfbEn69fHfz', error: 'null', listeningPort: '52578''
,Connecting to the localhost:52578
Connecting to the localhost:52578
Connecting to the localhost:52578
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
Connected to the localhost:52578
Connected to the localhost:52578
C,onnected to the localhost:52578
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 112 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 113 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [2, 4]
,ok 114 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] Session.startOutputStream(with:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [2, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] Session.startOutputStream(with:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] Session.startOutputStream(with:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received (13099 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server received all data: aFEmlYXGpzjZc7u2bP1smWIh95FdJyYFHYS5b8cLbGlWWZF61MHJE1eHBVlxpKyFAUwjofQVdGY9c8WfwW9j9d1677O4fYZgHn4sNWkZK3vhlD1daVdLu3jshP29zpnOThkUwH0n2koPoN0tdR7Qfip3YNQN9cqiDeRqxTBk5Sbt31VMrQ,sUnZ2F7u3LAEB9fGwGbtvRksdMcjU5y1fPfVOJ5SPBS2Oau4mWVVEv5BEJaT7wykGLE21qsDEsgoLkZOmW9JEMwOD2dQqFmfzIedJpENmgz29VOS9hWYKTDePZuPatWxwQq6PI6bNQFPex8au9LQcEscSKuGjrUkiBklhxdSgcRwrgYRDokhvCvSoD5Je3VpYVYhqs4findpOws2dK5ILefSVk8i8vcC5jBvfmhqfVuBbcmQtWpd4CRiZhY7e9M4,YlqQFoyBtHNxcV1KodRUI7xkKmhFtnBznDEsWcPOMuz2SrZYEcdHKFj04jXNNTTjq2Hn9ubULFrjSah1fwcWsbuFYxIEyTVI2QmhtYFTP6lC4xLevzPko2FN5woHkvvUZvecO6LCCZRQ7f5uMG2HlijbWk0AKyU5ACUc9GGGkO3BzAcWeLfdU9ozBPK13RJtH7SRLm2jCmE5xUS3xxM7IVFIgGlpfNKThMPzNdfL6IDYARKl0omN800ZEJSGq020,0DvHmzKPrPWPr7GKTb2G6S5yhAgFpTdmZPjB6ALAmf6oa267vwcTCnSYV5Y6bNxzJMzPwFheVXWbVpIFugOU8WIY075iEJEDCJOx2C39QqC0e2jmojxRJhDUiLtPllWV4d5Ts6fFJ1JtF61Eiz1eFpuKEQkqDjzFrNzNsKROw6MyjUbRG06KK7a2Gw7fvLMtkvLaoZC3qCKXoqyTD186RdeFnqsumYS98RjszMe0SPd4c4WTrBb8UaC1FjD0y7I,8,kI6R8fBwZSEchmQE67iw6aRcnMgG8VOYIimYKGVdEI1l96isSGuKJcH4ED6SkPiRimKzsM0jcJ8f5uLYzDvbqz5hzrd5dkp8UVKuwBfxnDqGKtf0f5Ijn6R2x2jaeYMN9HXBN2574bCnVct6xNsJEywjiXYlVxjwbtxFYeO8G28vTqw7JGl3FuS2Nw19dX4jCbuQOzIK6sH3bH3nPkUvk19GRp2b87DfOj13lj4fLYqmNQTcSIbdFhG1oyzGtVkx,GUu2qecVMo8ineTEOYlvPcQMqgjLIRVohe09EOmKFR7ctpF71J0NZWVsJbzgtf9qWHHPmb19rOYoUTTqLkMO16rv6YWoVzQtYl1snHDKlG4bvVZAF5tr3ihLFmqs6XhjZqysF3bWw4hkncYWiQiavZw9dO96SWGKbrbbt5UJpFLh7NQwuOrgmYa4yyqRQdZu58VpoE0dmG9cvOwOuQazmCnUE1fJQFoRZC81XdPbJdlfcJKGatAn8k8qJdOZQvss,zc5HcbIMWQyI6u3mW09VoJLRRqc9zasgWFXVGu2r7YOXJ9qByuR4dI8yO63d4KhZWsVVWmnc21hOCSErjebvqKKzKNgsPSY3q6J5F9ZCXLfpZePfXjgjOD25sD13W5z4n2kvg6rOauFPJfPXqylXkBbZG5FCgCo5ZGtbfuCtsjwFefoCQWW4yZvO7tZJp6SAxCfU6YTE4LGr1xic7m5N5UP5Be5Z15Jem80RvlblWJeE38guFsIVmGI1v8VBdN9Q,opYjxCDw4Byptw0ji8xmMI5DOZFart2zcQeYrFxUyN07C9QdzOXc7Pe8DX4sDueWuUhdHaemdYcM7UE2HBT5kCEZSZJBiaXCtIx9MwuPDGw1WnJTMNOzHhKP96cXdX2l7UNAgRiVCsc3TxMUqL0CKDEusWkI2YGWLjY44tnX851sVq7IZcLnGO32aXLrsiPa8H1Dq2C4owXMNHIz78FJTOR8svVyLnGFl4bSduSqie94FQIOkkdqTtY2ENKbzqY,O,uJemlOTrxaX6WTSPD5VYSpueVLOBeF1JpiIvHD0D8UlNP8pQ2LHObRi0pCuyFq9cQhbU8KVylhpBXpfNduCCuVZpTjkN0o8cwxADtki6o2rnX8NwtwVMIioKcNCplc5RIGtcrYM54ZG6PXjf0F1aYZMnn1kTOlZx64IcPhTjmBrJWy2XBXLQBGoH1kWBOZ28KX7IrXuqhHjEkkPgZ8veVn1Ig6TGAweFkFGzzEBWjNHD8Q3lxV7GrDff3MjnYukW,LMBXRl4Pi7OvytoXeqzKi5tA4wcWlI0ag4jXF2rvnTfSE2PHENLemBU4Vim32BZPx2CeMpbkgWkRLfXa92h5a7XwGcjIzXgKPknt4C9OY3YmMlybKrM0nemDXCBC7HE1TQQgEfaT7JJLfKYwntPjSKWzjNcDXZAH1bGpDTO9VLzx4jVCafNWRa0Zvq0oLp2prVgOUhn7h5VZFskF1d4Zk3BxI00OwFcgV0FbU9ziE4LrjeMCc5bRUDni8ltLDxvZ,yZiNo6F3fNicW4hymZyknUjBQXmgbauAEN8jyueHfEqJX69Hlx2yfMCIwO9zhZLIxod1R7dnhNidh1yNn00Aa3d3j3ISqitIndgbYMdNwHXUTjHJxR3I2ex77nn2rhtTze9GcV9MHVCsSxmBUawS4m2oq9NgOT2uxVWYUIrEkI5UuKODr6Za2yll4ebxFwb4fT1HUOsB8XCiymH0779GGXQQrwJllgAxYgUZI5NAsrCpYlm0utfq1laJ2APTzNJk,kYPqAuO7881XjhrjA0Aa1FZXCAYDwbUcBjfYDAw0GflqIrwgLk1KTvWsqZWikknc0BklCaejGziUlgRaSJXXcB6UG9cE56aNJc5idtDDYPq5MpV0i97yknaWpgJUbizMcOYRZTFNAcryyxxBx7Fd4EcsqHcSC4pm7Xl2sFGmGY6C7BJBDHa9AuF5mvwALzlj9iFfKDxD8oKGMk7G4XNzmbAf2PRubzqah52uxb8pLVHXoTUIvEZCTiORvsrvtxk,Y,2xBSVpXMVhs3jFldAfKZwM602rG5K9L4vnLwc19POYIRYMYRZMkxGLtoLlNXrqdjdrVddFQKXkqMt6piPjj0LOdvQa9y1uf5eci1Qtc007PpJAQt8Z6R1kZK8v0e1JggPXpG683BI6BMzD4LK3pxBvJiz4Kbs7cV7ggf2WhWcMjUNEmG781NrsOJly3iYW8Pbzf7qHYdB3pbGRWZw7OxPyIkeUrNVR1z9rJ2XoXMi85erd5CfC6U6EK33Pjf7g7c,Kr0DqWdCCnwRTVHKSoSVjQcPOzK6FLm3drmWfTSg7CA3n6fbvBxF5v9KKlET51AlrH72oYE7BNAUM5jlBJWGSqVIuhMAquFWrY4G6aFBm5afj7JQ5KPIYhGasc4roibupobGPMkHqKSdyw1n7FlSCOgmIPuApDSpou1Ce9c18eYngUknyAjX8yhf8b9nCRHkW4yABGjf9NjUzL5D2RPyvFrzCPpIlGcu1iPotPuv1TjtpGKkyPcpgbsGzISzlY8o,i3JgHRnjM01lcprOZdnuRvrbacDVxx6JsXxiPwECrjYbbRC2EEM13PN02Kixnp1H4PxHQ70oScfrzrcE5cya48Z7dQmU6xCqygJEA9UPlcybx5GhjZ6kS1CKIS8Sgq753ouopBN5erQEr5NPV1X5X0lefwNy7hMloo3hpKwbbfszMM7qjo1YHaME41PteCv2vuddwUH0ZEsJkHswCoYvNoTMFYoUf3U2JQn52pM1mUpXKJgHAqnz5aH82Lg0dfLX,Zqxcpx9XZ8D6aXkdcGXDUTqh8zRTDA4hnoSydFhZG3Hzzbt1de37YSzuIvjo5WcMiYU87a9hBya2T266c4JDIyOVw3A7ezxyCX4kBHkcPbgM8TXab3kC6biUia8ZjI90Orxk4VwaEymn9oqSm7BfgUWnf7jDi6K9de9gjMnREiZlw1ZS3ycSsdXUno6MH67t2mGcL2X9bLKpPmUdOPoiXyr79GIh1PJglbsrpk6NqwllOPUrGO0GGXHpUUkPCq4,s,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'
2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-18 09:52:05 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server received all data: dgSo3v3WogrE3cXeTgfQvlCmtO8PxPsXZ3EIzNtmSMYq4kRaVBOfbkz1rzxyUd9lZGp33PMBigF2hjtEhfU3EjOyuHxVIzJ6APo7LilRBPzE84uaX3xxhzoUKJFlYMzXxKOUmECRCbN1RhuGyL6JGLjbHA0DHzeSDrVMadylJapygMqX2r,5VXoCj7qOzwtqcbr5zcpHWcmmYPkjsVA8JyGhZ8N5EdziOkTk98dJilYYHkF9KvbqelICm4S2iBa54uevJddfsoCsbU4GljhjEq4HnnMRRLPlZFFAWyNVoABdtRxlBMbxu7ixAw9t3kywkzZgrIBeVfnDY8hUbTx3pcYQuK118OzjmK8e6bRCWqrWAkAeMeQc1anfA3n9U9xU4PE17wp4BCXithTbeU1SKpSsvfclMsSiYioNpQ10tfyW6EsLioe,x7KdrPVP57h7S5ozg54JBOveSCyEgQX2QvKqhLDg0kOaAXju25MnM8oc5H22QuoEBxBsQmM12opsxOA8xfNnPLdnKbZYOkkPJCEvsHqoAi23O497W6WXUceRawgmZMsdeJq9yczrQEPrjghlz526ajHGvR9iy79NimGfpMTMPWu4IDSryd7hoaypYF0sr6qhN6Fgl45tUDSoC8SEvwqaQpoameDf42K5CcKjECzBJcDf552w2QAzH7wdYz1tazOX,35UJIJJwiM1zpjlcsfJkzUfxRiIlWEo23OakVaYNlDQ6IXTw6QF7o2BbWybemSBHnGqxaxpVgQpnjmoiz20p5U2JsRE2Tgu5zx0xSLqluPyPbvMDwO6HVFgbNWJwve5JgZDNjoSqh1kIyAEfUTswNXXe7ZpfIWkiauYglBfzAnmchvdYJqyuxlAZIm0RNrqEX6v2TLNKZREZ6MEpnn7yqFHWNyZ1lZkdn0h05q5Un9VSwPQehFOhc0ggCl8S3Xx8,tVkVoejKbI92P1ITAQJpiDWWiJHSdfXSdTPgUG7u6IMlAzGD4DVAQFCu9HRoQMRWyDMOhNLmxZfOdMUzpdlRXeWrAICrJDIjZiiWhw4sQnmeBCSLOco3HEGeZcMPP74Jt0xL2J3gQ9oJWIrbq4b6PyMKyarI4nWRQNuoPlgXUd0hTyrWCrQ72fSs3JSEjRBqpeWq9wrY8zGbRtbHBeotfzRmpSnGVAXr9XrlHsLUCC4bKP1xEFguwGhPW2rdKvqM,CGyEhawiFpvX2a5VcZdwDE0GeWxrzZEGOdMVcQxh8GJPt9ZNW7PUJnicW7ycqUY4HKUgJ09VLFxoL7l2UCYBO6oHVUOp5ZiRz95tyswQCeOqT4Dho4gDaF86TvlxdcLHSEgeHMGeu21oMYLO4X0V5bAmlPvSCU9omhtSx9IPOroHekwc5ja3E7vyqcBEaWCuCFVINr0BJsCOx4tpVyuOmvAJ0XzkfIaPjhkmGaE7J7mgCgeVbQnKvBTbP5FFODAB,IhK57gdfTGxwGa3R7ycQPkFUUVhx8eM8JHXD5ciIoEd7TD3fj7V5R5b4eCpGSgu7j049Tv3eIPwqfPuhbPbTiZKIknBKQYLBZ13SQaETImaDtQIKGpLoHUd2T6D709uBYnHpQNUkr94ByUbEk4m42QJGBcXcy9sjLzqLuWCwiOtfUzXOp4rctd6QIqHlXNW3hJKGzY3RsuGicqaH2s8TqXvSkQpBbeBFdHss7xXZrmVvpFow6JTvMI0eyqzA5MhY,7ofOcYRznpTF9NaQ3SQ35uZL3lcGcbX30ILlbQaJwkIvImbifnOW13HpowTP6pjHat3fUmNe4aYN4q7PzLUPtRBej9cTKSmSioMRtso8T5PteGOulrWOfXTknnXNxD5kycQYwNgsAR2kjCxmh2Oil5c4KrDa9YHrbacy3gBpF0QHXkMqPqY8VCfH4btgPPXDY0BZ0x8BRd7uFvSYeZcNVLkUM9VUpj7PZiIRh8bIFTxY1rwg0lROoWaFo5dlJK6G,B1J6qgMF2HKB9cZSaI4ook72KBkVT2qYqzzzwf1OCQHjXM2H1wkRZZFzPY1hNwUJNQIuhci71pC9qix5yCr2sT1BGb8sXk6vVeJoijVpu21162OyJPPYvodoRKZQjsoXFBuflKcTRwa1KgE2lj4rQoHzEeoVCly64Btldkatuha4KM8voZwxyq85TwP4cxTO9X6WFigxIY5uHDWuCnd3OX4oDbe5tjdegsLMc9QbJiIyJgi2eJeXZ9yiKViIV63k,NCMMESIVNJSOEwY30PDZhPouXHdir0EAL14D1dBvYdMgplpvZqnZ4lhFH1iNiOhEyeZYUR9mDCT6S9ZumUbmKMcdfP7fjqhLJvwD82kVVXsNhafaYcNfQ1WJwI3uezsUawsPHKMuxCGvVB6UqCTlcH6lJXi3sBOhV39qQcpqKlmM21WOBhhc94MzgKiyMHNwj3297gKYkNq70nbEIoee4ztS2yO6uMcL3Q8ObwpGGk3jOx2v0HnqaTPaUkgriRgg,psmub8iJwLPTDS5yKEoP9K3JxUdz5txX2RO8AhcO0Xb7IIc6XZeQa67FgTZgfuge5pfYFhOOYgiPGYFNCr2O4Q5GLun6BqnfYfxsXdkJiQQinZTaC418LXxNKpYh7ijpis8JCivwdOMQXHoR5Y3EYSJjBDEg9JaHwtawb4geMNgDUSAyJfJ0Abqxqc29piXon032lLkzsUnPCwHxS4vCccM8SHGlwAwwXp2WbXS9evvXsObkZ5Fryi054yVCKvim,0Ah1cmXinY6zozm08LSlahsVrHdkLwIcxCAJkz0bPZATgznMcW91PujxqbHVnB151BeGULxw5ShHHG6SnXAhhifr4SNAC0yuufRm6MAYpt5LrCQopkxpKpZd2QsOEumd8lddbN6zip6FGqGxLkjgIBs5E0h7omuUQpzP4S7bYXPVoJu50bzanHHcSUm8jXMguMnuFsAKMNu47qS5MICWK8JZo6jSaIWv9WHq0AyprW6LdMNcZ3H8lxqEpcEf14XN,8HTwMCGQ3nz3sSg0oMCVQnuOZvw9zNxn4mKKskftPZ6hcYpwyj6UULL1XdmzSaCp5svjjfklC3FEgjDcltDnOaT73PFp9aQcyNX16WYKAMDG6PT28WnpeUyV4Yxr0Ix6wDoLyJHIWj6ss3PDmShojdmFJJQhelr0hwPIPCA14WvgggrkXa4bOjuWJUP61unNAPtQX5qyc2zQNQjaUNxhJgiHADuCqf7RoOYS13YMLaN9GZJeXgvRwD5OGH2U3O4C,Q7rVCx0ILYb48c6u6Q56MvDOqQWTv2eM8x07oRfSFyiwDMKieLa27vdxW50LvADlA3FQmG9FaBUHmCu5TAJeoyOSQU5uvbljaBIjdhZZRKUR5TTi7srir7PdrxhwSWHNZfKhM8551A7bj2hOwRKvmmJtBuJd0LyPK9pqPSc24LPJFGRzuPznzIfjAfOgfPgHTJM1z2z5bzP1o2eliMWQBwqkAOFSbsGa0eQH7dQEnOYh11Zpj6hZCk1bN1rZ4xyG,pBS2LYMpVsR51ud0V18RkYkbBzjOzqnAEdfA8AJybakxIvq58n3NaOYot1Pu0mRVzSu3gj699j85pnXuRGVDyfZC1VuGpf3Xfv0mktZmxR4VymGQnXlc2SgBdXBKi9Rf4EebC9NqLhIQ35MDREk22EuJPOHweoXRKxSbo7f7eJjECzmkAK9hD4kIvnDBF8tjgH5YYUcpC0krwcDmUFjRmHtlZFhYvIKenWVIdXyBzN4kvxzFF3yQ5tMndgcxRs4E,e4uUZ8aQ4BzfbZ4HnBHMd4CzpYfzp0ZcgxSkKX09WhPQCbw9OrASSGDoCXkCzDQBo8Ml6htE3p9tCQRy1xTyPJ7cRFiSozMoYh8GUDYNIgtS1WbxX8romk4C0ufb4wgp1VcwwxHqAx3gF0s5BnoUc5KucM776ODXzKIbYE7rMChKVlRoLkIFCub4I72T6XF4AZQJ9xt0c9mRutWyCXZ7rgkUC86WEUdkLjsbEaJWz9JGt9q4JvF2N8HH4nmkuyWa,1CChHKRp1N0Sd0bmZnHoVPCENV3taQHmVz0PuRG6hvyiiNbvaMzEdxLWElagNaYCn7nPz1tU5kn4adFSXlEpbcO4dkmc3r9WbJe3AIdzEmbzFXWswEbsKOn7ISZoqTEFtIic8GTQDiCmY6yEd7q5YQaqQlVWGTELZd11gWfDq7ycMoNvIEGNUGFpVjbjvFlxOzaT59cq4U2ZaSKftYKBpJI1szAJfh8msawAMEtGJ22pTMTMZR0lqdQPIPmr4EcV,95PPMXcAxdd04xJwRWMcH2a2mLK6IIzeu4vMGQLnRroyMrfmlPLHuPKk2PZLtPiDZwDOTzhA4SCHsrqpZKw8op5O5GEclh5GgD1c0bRn84W9McWskCT0Xo7F7FpS97YQYRvInyKCzWG531ZVHUzBDdWbFVjeOUrpWaQXzQvL2FYvvc8INf8gD3TpS6TKd7vuSRRX3x7JDWCGKSSgDRTIdTPUmwulJKLGlUfrIiaWrtHlHmxSR2joaYdA1TYrp03I,wmjOTwG5WqUE90UplUTY4sDSI8toRUBm47MWQvbydXYUJHkNc3A9bTXzWGzEMSpLUCAdesuObfES2JAxKjXxQ44DNOVNO1PIRvjlhRGoHfnIWVZta2MljINMXO7BCDVwJGtSrOqeAJlQUwR7M2xiPoGMnNO1I5WTECDWuuJx9Cvy6wPQDZKRBsd0lDnzohS0Xv2a44bgkzyc7w9nfl3vnWeHdJ34txedimglQc4LOAPHo2RKX4xbac3zz59tlx4G,cq6lWJTY9FiqWckfpgX3Cy73SsigufWo51yTjeP1a83LGZqQI5opOkEvOG5yQcVWWo9kuylPAtgzMKFFghPrW6Mn6euMs2I2kPNNOmdBZaNIcQxpbgwVFcPIbPi6t353kTRHUnAjXQfWnxsDXvfIWbGqc8dER96YkBfE2ZlE8WpO3nXu3KJsfP3M3jKIYAAUZIsHyx5yRqOVzC505NaAavwKUXvR3WvpU2lXx8OeMrpI1DtlybqTqxN0GB3OdhJr,t1GAVZARBVqp0lipXbDfvoInwAYQ8GZaTGRBxKWfM3lHKzay6uNMkyV0OQ7BhbCUxIS8r1OyGMpnVY1H4G5NXrLhxbeP7yaTkBJrW2Niu4UijqFOJBPVLGf1smvAwlKkIyNix5mUmimDCHQgjsF48zw9b93Zvdw4DfOaczYR6SSQ4y0FmTJRdrZnCOj9SIq7ELvhXqkkAnFoAIeewfe8TuofYpw6cz6epvZSmZVsfbem85T5aWvoMtTATclyiDAv,FRoxqIr4NJpGiQNkyaBtjqKk8EDRJBT9fVgm5ADWg9uqbNa7JTBXfKpnzyTZgLiAXBsfdCtDcm6PJVig3b4sJPEdMeXaIFYhbAAqpQb5sChO91DZYOUjVRuLZK1BijALgWrOH2XjKy9wMtpZldxAQbkWZvWlzaCt18uEfoQZMqfsvpBRR89j5L8Vdx40Gtb1zUovXKn8jwt1pR78lgjcTqkN7AylWfZMSvp6eLlWg2igWDo9up8wwHRrxSOT9YWu,J1iZVcCorXOIuebTnlNtDmil8vZpomELH00clULzXGHSxZ2H6MVoS9ApkQzZxe4RRoTrs1x2jeAkIR8vKhZfhgqJrr35hA0kgGvk20N68RdcFgPJJu9OGMf7Uqi5iFe76jdBGyFBZ9806TRgQWHJFqSjLsPD1zYc7U8LGLc3ktTbcAN8ZF9MDtEckDlR8fX5CPvRSLRq1reqn87nc5m4VflYFYCjSvyZf8nLRRgjw08SR2e5GR51gv5hmPVdJU3R,advu2K99EVE9kvFAfL0FOERapkR0X4S0NjlST6VEP3OlIH8Crt1FTvuhXkNL8h02Sd31iaSxkttGY7R8Xo3btFDKENDIF4btrroZREXzfqfjTOK3x2iyf20KiQX0yhmBzpMOHW707sN6Wmphyuvn6vH9NafAq3qEKZxBWFJezMWq1UoyEB4hh2NGq6jbnn9ztYXBorS6WBaKYW4NclWCgTabaY0ijg4dAQ8XjH8j8oSo5AnOez0qqWNLC6Ig9eN2,iUnVEEyz2PeuJvpzPRkzbxLudU3TGAlnoyRIjUq04eDWlanne1Q03IBYbAdvZeqPV1PVYJZcTfmMQLjjlWGMVaEpw9mZCCJdAnM1c70Yt74JOrrYd24elOskwCbSyqDHBHTe7t4RpjqTSlsZ2RVkyTjRo6byh1RLRMvK99qlQFlJtyX4XuXvTMWXmkYxt4DV33O01jyGBVIEr6Znn39f0AeqZAA8RdQR4RQP81WG5bZJbjcSqip2PGiaOfPVvjeA,UYk7yXeUa97jU9rptG0UZU13mvCkhvfLUBnKGKqQ88nYso3s8X0GtS3NNCNdRr3fvWOOo1riKDiPgFZQnh6uPfp5lrc2HsDnvnKmM1YsZvDk6DHNDEQl6IaV8fia9NNwHpIdDzzmhWBpybsXQB43nMM6JEgCBI30WJmQZtqUYsFDGOrUPFRDWAbsa8gAVd5yGJfEiXAQQuT9Z4ondNTLG5v6cZ6AT5c5xBi5VrDkEPwsml54BF5vhdKdwp0531JK,WBHlW3mGy2QCEKVyffV91FkKEAs1H2zFTlNjCorp2pniSAZuY0TFHOkKzqR9WFPKsctDGtQ7lW8g1KCNFKhnUFyMqwLhib1GcbamUfjVVr4H76pIgpR9P2Mk4HgCrvkwkaIk6dfLBcjPHEz1T6wUFUFhbr5eUHhSVEK1UZVpmcvUl9UB4oze8fw4c0xjZ9B97jrp2II8WPlcXRQl3Z1zxv8Yw32ScIWQYxx8F1NcPcxQFnecQJ8U4QCAt7uPiaLC,EqsWepsRFjfeHnbISbBM4toCU5yXUAjnW9Wex4dnZcalLygP9zFXJH0HbmJQW6mDqJXvTrqWSA8nTh3fA62tt3pjSd8hXOAG6gLCqByDDIpKpMMKOQP8jfdgwd9fKTcKhhoE0ay5PWKwGvLwxPGYQ0kO6LDFpppjbWy9ep6yZVcq5FYFODsFoEnA87XbjFFZ0TxLW4ctAYYvIAGmTzOpELaTqLIjIdvDkOh6mnptz0Zy68Hh5gP6gatY3l5u9Wr6,GMzlR8djSiOZDGOn3A3sbiaUPm7CVPNnBAygOuWOujKVlMnSbqfeg6yvsYP9LlW0THAMQHwDx5hyLe8nUAJm3RrmLwvY2ZEm8fI8aYVdrzX3RltJh9mnhutL7sObZOanNihWwNdn8PfVOmJGy359D7AlnJ8Nxm9ngY0oCeA9U3RymMcIUOTy5QajPWnVW5rl3bKYqBTFgu0THXXl2AaNJ5l7KpwJLddfi6eHMz5jFnFBvBtDGU8WGcOg30jNWExn,oRYk1eNSbn1MZnPVIoW9szxFsgSR325FeIXHqKPPKGRJaml9FhHmhQsYyMRdDWW0s0BtatTHG8m4fPiz4EayLzSIBTg9ePedvl181JUVCPom2o6JB55wu3uiqsiyqo56P4AO6gblUL9jJF2EEu0pZnJEO0v33aNWczHAsfhw7sZhkKeyP4agUyp7naNfROsYoGspgZWk58zJXMRtlcseKkPl8Pp2wxNij3uHwBJk0df12v9wla87NfYlc1NZKipJ,Z3AyOKFV9uDE5c3YmlWCfk93KcfoOjBKNOaFOyP8KQ2AqmlrHb65OxMznzjWC8nyivgjkMjeTSBByDk7Mi1Nu2RZhcx6DmJHyQBtcIksh5y8ICporpUpVjWJ4GHyxgVAGkgPYkL8Qw84awiz453VbyU9LXlo5107vaQkKFPTsh1z9jo8mtCNINJnrtlrgL2BTDExtXjxju0rlbCtK8UendbVSipjlYnJmcZH8r91mITKBZWJL5fYojnagc5YNmFN,cgiiVmr2gE0tanQruFgufbbZo7Ivb1jfbBJjoQ2PZacxRmueNZvCgQtAKywlRLJnMKhOAXOAtVM5q1HzAS63hv5e9gSxceEqmxQEw1mWP6nPTgnj41aKSGCZmq7ZpMgbSxSbqPNWfAthYarecBeMH8n0Zk1Um5cr2QimZ8opkzNU0CZkjUwN2f7HNDsfinQngUL8BJYQHm0RJRjFSfvLKPLgEsCZUMglY8odJVKYY6HczAPVq7IDX9ZR4j4hll9P,FSokMsfwiPYVMLeneT482LiLAClBLfLfBnn9y4uOQJnopdgaKjbYj1827QsCZRzDTlpRXtN3SyYECchxRbvphSzWmjdyhvj98X4Q5vUpRKI67R3B4pjwa9765KJszMCtqfzFN0JyRTcqJtzubTQ47MQADwGeUdQd0QZR4ddsRTiJh9BgkhKKw6GJZq6ZlNED4frbQa6ESWEMc01t71ad2qKfYsHnrUL483yi1peixjI6NqTCwGtLkLmliHsuMZTf,kwzY8Br1UOuZJht0llSu8kaE9p0xA8yewg5uTLHXi9RIZY2uyrppR4upyTuRf18UtLolGzY7DSccmhTpzyjBQNOiPdGDXlC0Ri98kwn0ZQZmBTA1TFv24WomQPJJRByxyKhAChlWmVT3a0ifEx23ELliXJtiLirBZAeZ5fF5HC83C7vii9magyjImnGOMLCeLgxUIdOtrWSfXPib4RpWOlnh6gcm7lZK6MtpqMoe12YuZtZGxJGbZqtNqFYHC6WV,DiccIEeEfUuiSdqL0SgCADsPgt6DY34dTqmSg2bhtXHTAAFatE22uWKoJADO11ZJUOxqCn7nju55jtQsGDxj3A8uyEhPlbuE8JbW96WIJHiiK3rD9T91OeTd9HEmvT1Bdy1NvZXzJN47Z1hdxmfSTTEnzslN5jwuWZxMA0sTfYabP1cD38F9ofuVGtue7HI84tYRaKlPdN9kXKVnN9SuqaLcLk2SXM2zbCUG9iblVB59EUXzPDL9RzhmoXllmjJz,zc8RpBvyj12zAb52G3U60HJNDFd1qOfdTntg4iQNr6HZ0htryYKnU49S1bx4M1YahO81isntne4DFIRAR98wiMybXAS1K39BCBxznrxUGhQyr2XFvjDwfx8rNHzqbUJjaTKoxXbiQExyq6qYLqynGNBj4XPxkCCRsDEhstwsq4vj8Ui0sYGWwe2v9li6IdS7Ylay5VB7tvvGzkf7f6iXMhGndhdKg3Ok1iusuy2LkoyaCjPD5P2wcTnGbHs1wJnF,wdoPPQYXgniWcCbuiD1KhjKHEW6ukIybfjZ9TaRR0P630eTTwraSdgzctIchFOORAqV4vrAq9d5dj90dpBDMfisy6hB7gDZShiWVNCgsWujOoEVExUz1Dj1nFftecg5GFsa1F6ri0mOb8ONkSYZwgYNxs075bR4Ol4EGcOmnRsH9JqoOtxEETBZKNyayiW2L7WaPFzcnGwnseLCVFDOhgI2QgQjwi14fURleXq9hjvrOtWRAbHP09wNJQXugDcPD,JQ3XgWOD0ERHkW3Eu1jBMqnUZjulZ5fDQIb3m1Qmfe7qS86dxlrZzg9aq7Vk7PizGrVEnBnpgdoAv0Xu3wG9HQlM4QaZppFLflvBmjT6S4FUSJ9wpjjxmoF8y9SFqyZyezO6Cr9py0Dnz4vZ6qDpkSupSYWJHjqMiWUveyDG3Aq0K1D6Y3IdXYsgeb4B3BUIJpMEaLhKFHRf9Qpwsb8wgxCuqyK4bHQEo5U2d5EN2mkVx5rdgt8WSaDjmXujBAmh,nbsGE9HtVdHVQtAx2LL30Zm52Y1TcGROEoI1l8nRrX5DLWMIZUDiWa8eLHtMqHOdU0HGMznV8YoPlqvwCNPhbFUxLDEBDgSSDuAJubFQ2Pg89LC1qz09Aj3GdCb1sfCEXU8AyAWpxsmjm3mC9wgAboUUW6PoXdy3th9tRiOptebgQ7kyKvveeIAo7BHQNGvX8Lp09EvR55R5Qm8WiLbWvrfm61AuwAcApI2R5U3lOPSSTuxMDN6g4RiUS9IwUvOz,LM4GNFZPKVdFeF1cufwgwuM94cJ0CKHPJyzX02jXKKla217I1HAScWo5k4klPUDmleqcHaPJolD12k79jAWi5zRof3FYlSJk0JmrZZXYHYUTxhwyIaAmiWTQrrFi5JfIiX4LR3Ygq29UWNcZhoKmMxKmje15icYzRkH9cN7psc3sxhB26aQswJUImJi570FOTFKZD31rsV11FI3bOZecojJ7unlxi4DNnDztPVU15sGVklYsoUnLUpmJfz9xz6sy,hUaZj5Wy0J5Y2zvZ2qG4CbESctU0iUDXmu2w5tAiquIWhGb7ISixiFGqRe5HL0MHLBYapXswnAbtQsRmr8jtj5JBR1YxWdMo8ZF2dA7QolurThXq8eN8CzWI3tpQv9T5WAjS9do40MPm2HQaSMf3sj5gyjprtwpNJQ9vZcEsC68rD7Bp2CgMM1fPdntpQEZHqVi839LTyLcg3FnnXzmVKrCeuXQwFLSGgG29gLFAshhuWTL6a4xzecHvJC4q75N7,nbgMoupNWKBMewNP0BD8o5fbMNMVdlS0cyNW9OmxfryDJi0AXLeowtYq7Kl1o1iMlqpYUHwR8BoiowH6tPu1DIvd3cmm5eRdo7SFQ62VsKD6AoaJ4ArpciPhvFdC3Dbl3UHG6n3S5jOMF3QhRhZl3NDk5z6dGBUPFFpJUrxrOmt4p9yaFmFJ1Jm1EndZfUmdLiCnUN0AkG2Bm9mCgQwp2l6vZLxsKyKSqHVWn4AnCPpIOxikSMiIMNixAsIoVhPr,lBCKnLPyS9hwiLtqVCPFGssCAx2FTB5Amz13T6gFEZGxyPgBhhcnYFAFR5FYYJa73ADWgCpqqP9ZGUoyym1diCtJggMnJixzLWQGPIYbJ1mXd5FptqgmjxQfT6bZWsF9zpuL09S2eQq4Z3bax76XHcoiUJsbHkyMaGN8HhMQ5FjTSJjI7zDPK6CUv2Q4IIkbXK1XJTlp50JIuc2TPzZhCQwUgKXEOWmXeVM2XQYOHcXRJ32gPB0hZvUxj5vDLiQb,lcQPLxtW1XxL6TPMjln55kN2PzDMkbo3MDZK0eFfO9u8yGc2zPoG57MIef1rDiNPb49j4jdr8Vit7chlz4i4O7ieTm041YxckxPRZI8RLXDpinARTeN91QkZdoU1lb5RmtXdhsuNV2UDzP0jRA5RzYZoVrlIbk0ebndpkPNDQbYwtVRwUOjPEKCJWLoBgkZxJJ7dl5o91U3ddzOeT8I1sbbcT2s7J1rLUZ7kelkSD0V5H9Qq0AP9piHr3m2wyfEA,b3zTYoRwvKp8abB8aMGBDiVMTeIZcmFtYpiY4fuBQf409SQO8S2wZM0w4WVPiknJuTTfDnii85jbTB4XlbIZSYqqY8T8av73Mu9tamU3PIpnpbQBQeSS4wy2jLcgoHDfP51TImP181KsfsldRD8JEDDbNbBIDduwCXHVETXPNoWJEb7gXdgic6Pf24xzuUikW06TxvSg85FYdFMHBTm7YXZ8smi1vlIjz47Kw7LyPTqWagwP7zU1A3BXUnq5WTMf,5LyipONfqDMkk3ZwjZS6knWqkFjh4c1JOAhqS5M8rA2HzGC6e4vYvtjyCQ3f88tKqEy5rCkNhv7RkT4Sdl8Rfax1kKadCIlyahbCY6Z479ciHzledl4pDYLUCdpGNFZNbHWlpDrqUkOEfXKI3KfFvsvosT0ahJgojWUzljZwcLCKmUUscZY00Omle1z90q4EsHlAZTDsMKTUUE1qg7va8wCFPvBDA2Xh6z0stzCxrx6sfyCWCviHkrbzFdpbPynE,KED9mPwUvjzKJZiuXsF5UYp8DN52k1K8lMtZK98X2P1cK8JRkOezAuOYoKG49QF94t3lFYUWWdA9dJkSqem3XQrF7LYY6frZS1mCmSUDq6ZAJDtvJ8Qrw3EqKn31O4yRALfd0LChfjXE4BZzFu0az34DgiK4zQbzFQoxMMHo8MsI6NAqaLjv0HAqyNe3ROrL3bWdn1Af9QIkY7CVEww8lDvE8COnP2CBk7CLi7OKROiBooWGYWN6oQ85yMLREvCX,aoDyOKJRLR2KMKSs6nGfs1e6mApmzep9yawXwcdMxrjPoCsii0kZXXlXWN0ra1NCXO4AXOsRY6Ae6HiuID6c44BXhDJftwG5zGaPwve8RHr3B7XnIq78UnXjgat1tofdmKMwS5nQ2Wsse07mlVhQVEjN7U2mTXC8upnxFs3KuqkBmOiBKGOIut7VZmCPMwRvKXW9Hz1Wryag0QiNN5IIA262SGR6OAJaIHqjbIC3vrguSLO9gJSffZbzF8eMetnI,krfotkxfSkKqPboisI8N8701vlmcuOD5M7YDCpr2F3H96gBVjJHBhUWKknZDkyRYyWMvHBq7vmwJB2pofp1lzhc8RlqBY7qFxoNcq4z1fjh4yf6b60vArj2HG5qXC5xUL93Dr2AswrAQTcEaqppgGPuDLPRFxOIIXZD5d0V2dU9Fnc9VSh8KexhDCsJAZiMz7cbERAKS1I3yFZBgadnKuafjbB4IOsVCwAFlPZPSeDK0hgFskORBMECKofy7S3Ak,CRwhm2hPDwn4DEVlF7ViqwMH4p5Vvu0gnuaJMsDKWukxnlK5KEnHaUQ8ZOA4UywzHhBTYxb4SCwxUb0atj40wr6taophVfyVk6MNxFODkmrh3qM5Z8vDeOxmbdVG6tiFDkHzuyIsu2w8lcORbLVzHq985kHIGp8InHMhLhod3GeCPev2cgnRIR0hXS2cVsCtFNQCxI8QtJiRpGm1Plly7c8jdl2VWbyiZsCr7R8ymFgKPJrXoY5c4xkBepX4htLM,V0zwxr0wjkUgB5OtaQNK8HA9y7wWKvKsT5RS7O9kjNoCktmwrm7aBZCtIG0MDpPa9Rt14qpiIG3E0oqXitEjTo0ome6JDRjN38prC4wkaZlozUpphE1Z6UTyI1Cavpf8FOZeF4YnXayqFK1jtfKgLXZBQo9HtIZW4FC8gH6WE5WVRnhPIfI8fomLNUFlQTkpuSLjEMs27uDC10Lk4QpKbf3SsKyWksTeYJoafQd71fgmZMWRzvcQlmZi2ARkfS7w,dYmRniVcolEImmbSoQX2sfkItE06uVhtjoole7q9oFiwXLRmejVOTFbO7iKpAaBb1Cs2C6O1fBwGrq9YwXBE1KqkRuK3RTUNXCl8GY6W4PZTUCMA8qQM02s3rx6K6fMLYPDqGUCqDqsWORK3QH4QY0M58MLRodZKxRCwi4LkBcHThTsFl763ZSoylRyOmeOttCZoULXQmoshfRpTTUx0nK4HG23FeSMnKrd9v9XRM8AvC9AwiFxjwB9yqDH8emQ9,uO7Vi8qPZ7yPJARi51fb9CRNuwqMQDMDquFzcGYTUhvUhMNql5KChYRJdeQ7mxL6ivoVTddemWDjibI4AvFrQjSZZVnd15v52OsriHUaJkdpHoag2HOM8LZSKlVqXZz2xsM4epN1qUOmuz6BSfez5Vxi60Emg9iqQLeXY3HU82bPL1YaqNmexzQFomFcO4r3bVnBLlPZNQe9UEeutYWzMUDNmJ0gv9veEitUY09qPZJ3qHfSFw5OPbN4p5gSFI4X,ONh1BoukMJuEDfIMv6eDvD6owZXIUlag06J5iLO2IUTo4UVejVtcZy82McS3wWTPowrhQ3PeBXeZdaDdqjzWpzk5uOA6Gge5rkAOJoABDYp94UegkApMTiLYxhhxTUllcq5dvU1MEfM2w1F9A7CYlk52FYx4GyooSp7q20KnzaeHSjK50ZSxY3PAu1BH7z9OJJvOaYsMGXBM6rLPvmfT8IJLowoDblVVAHYvsobaLesjf4x89c6Ecz6LFlhntIVr,bJ9z1reoAgm4BGt2lDqTpaqRsKQF80zKp1sAf0CnVuwbLQkBabAe1X8NJPglYMFgthfogxF2vyp7CDuI4cplqJ59vRKWNUFcLLBNUEWLrxu9APETbe2M1lAAe0GRORpkoutgSUS4nLQvdg0BCNXpiAsxx8Lg8HCLHWOosE8IVcFBdUSpcGvQ9D2z8Ca93RY1Kn3TVr9dqohxdw3DPqEltAmS85ZHKG7rhmpHmvKzbbLfw0fd79bYVsrbAuVL8l9l,8HlCHpnvywgF8cZuIxcE3FOrBpuhaX9MgrYQCHKKe1EyyKg0tWwx5OqdwPev0DoiD6R72cw8ASkFrUfYMCWIXcHwlUbtDdrKtDQ10PTvGeiYQWGDPPURBrSxJZ3ZIEO5wLWmYRN2UZWrG9wGIhEH6maOFP6ZPmF2WoqZEK6S8RpTto2Dbp0Qc34vV1myepIz2WmSKv91qbjg7pchTeC1tTCdE0EZuE0KjhiONvBiOHzSTzRBpcDdtGSUHhvsyysy,rOW3OWrZOCVGhPYHPmar7NtacPjgAKNUJHVlLFCPAaKTSwwL6jWXIeVo3RlzOw1Rw0vJKOihXkqsrGYUs1rRsEg5ESKJNToGyTJESZILTXuI2fbsMTCPQX6VDOD4Qn384DICIRqemq6LnjcXy51CowXHVTUXsPXJgmSyrEP1xTCAn7NkltUL0jVY0BTvIysGqlszrFtOlLDXLmHkcdRiNy6T0ScAWetjYE7JRoT1m4yQlEHXbDRQk7IIEyO6en9g,P1kKsublEWYa7Q6clvKV6aJ6EPy3wHynf63LiEaSAUCuS2TRkjF3tPkjzrPkLIfFlhhlU1NEgOzF2bhj6LIie23qOaDqRUOMSaz12FWWjOAPV6DTXdyJxzNwXR8LIjCy0Gbqz6LMIYqyp3Odn9TIjyh2NseAwPvBmNnIstFzTm5WUoh4qtdBRKSoOAUtzxQ31b7d1OwWWYOYntBPpJhtnwIQgPfZz0bhEzrUfGb8aKsTsmZemCYlQJiYJxJLocms,RCiGDAbOHhvVV7kLyDu7gd5O6JmGCcURPI3l2VkI8TJObW98jNAn75ttixLFhqCsNXOS8RFBSChhYYhA4oQmc2k8gqy8MsFPX5NX2HJbFPDIskcVa4FHnO0f4XmD3gyaYOQdCW3dS6v9kpbhh9dZxAL74bnMwcC9PZ2esshIDb0YQhbUvZc00EGTSs3wyBcdglYgm2vcOBDNJ7Mo6P67wv7wqXjhs5CvjdN1FXvWBVRegsB8DOoz5MYozQJwpQtA,bZHy6mqOy6s2GCkZYo1NeHxJcPRLCGIRImSakAxpmRa1pKeM13U7YsK22GYufSTvezMV78hnTlWKUUSejYUJxoYSJI13o8KhP5SVwIrm5KSgcn61DuysguWWImvSbfyCMUVxI455Hgaaq5Pv5TkZTShRJoDcS3BS65uMhi2Ox72A8hBH8BXbBmOgF9mKMsRplm2PswF9ptLQmVMV5o37DQ2BTj1Ri7fapDtCmx3GEZCa5SSyOmstCXvxVHrHCvTo,GpVMjTYdgk36yYLMW1gXRFKa3dBOefohwJLvbr09tC4wU3vBodrpISlcItoHaHxnkparA6JvRYBIxRUkpOY6ROhtUVnIhr6AwmeMxBkiWHckhkTAJiKU7kEYRJgKwhRfrAArz7N9StNOdYHQ406Ipczz2JpyCKy8659crPtrfP9dLP82nvTN8xfqRm8CWFmfGXXDhxDtoUhTAz8BN9TBuQxSJtKAncvpN3Ze8qY0prkAOs6Ad96YZpVaMLbezc57,p8ivUnPbxsGMRPXgOdVFkY3bQFXFISyil2mUNJlC51xuaQzupBXDFR5vq3XbsSo7LAIhqW81YeZcwB5HvgIHth0Tw6VpsI71gtkgjfHc5s7rLEuovgY6SZxbMFK3xXzsNoYDoaZh5xsHXtvToBPq8IjbCOeoeyVk4k8C7miHqL7JC4Jx2zZ8LGFMvjgxZtw0ek7pV0jhswNJ2nzK3fH0Gpa4f4qYcmR9Iw9c1dNmnHHIVU2QX38xrdtSQKmHNjEM,ipTRvB0I6I0Z5gojAVI8mT8ZvxysOB7kqpVRRhNAbM3xtT6F6Rs7k8ABcsP2nKSqSWRm0PNWUhnSOKl9tmcj65FLNZyKnsziLASMqGWKpQrouU0ue5Ad10j0okCyEsXIDQtLxrH66L1W1oWELGsl2Styl8NxoyZ416pR7PKTmGoIrvt98AMxF9rh5EBYqhQ3CRCpJLfy0Cbxs9FjujTTSvCTSZz16NjAP6UBMLjYbBlUtiuEIgFM7kS80fgRV7Uk,R1hFa7I9AaJISiarMA9IctMikEpmAZO2ScUzYYgve27RJv1bVp6rkZHdLTMkbZksGcvR3jguegoLbrrBO1WpWsfiYUIkFMARnNKjbKvPh30cHO8DukUMReCVz95IHeUgdDpXiwJusVHwi3j4ivdnsQ285Cggcl2Qop2UhFcZmjsV0YAN5LEzw36s5319VkgWdj5BiU3LcrqCJZwe9z57FnD8heR8xXTRx1XmIean2kBErqf9Kx3SlBOxVz581gnR,qw6xk0CVnL1fuBNbtnZwS69qWgYbb2qN3bR7Tgz4RlRs0zZuQf3RVyWAWywrmdso2PWlNfcPb6VuWY'
2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
,[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 4, 6, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2, 4, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server received (15289 bytes):'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-18 09:52:06 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [2, 4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:13A16B2D-9A9A-4856-BD41-17E83D3985F1
2017-07-18 09:52:10 - DEBUG thaliMobileNativeWr,apper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopAdvertisi,ngAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52578
[Thali,Core] Session.disconnect() peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "13A16B2D-9A9A-4856-BD41-17E83D3985F1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:D8F1A2FC-3CA8-4908-9C55-3E5C06DA6244
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7DE26A7A-5E15-49DC-9309-AE715C12E4A1
,2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:2A47748E-E737-48A2-8C9C-5D3927DC5FFA
[ThaliCore] Browser.startListening
2017-07-18 09:52:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive",:true}'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:52:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
2017-07-18 09:52:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15","generation":0}'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15, (syncValue: f8fBVEQmQXDgrrKCU3Xts8nq4F8WXSMf)'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8,E5C15", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"2B7CA6F7-3F9F-4284-8D14-32237A26476F","generation":0}'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] ,Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
2017-07-18 09:52:11 - DEBUG thaliMobileN,a,tiveTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","generation":0}'
,2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
2017-07-18 09:52:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"74EEA8D0-8560-4241-8408-D752D9A14577","generation":0}'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerA,v,ailable":true,"peerIdentifier":"624396A9-3501-4E23-BC49-2F10FDE3AE33","generation":0}'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DE26A7A-5E15-49DC-9309-AE715C12E4A1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,F1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,F1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,F1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,F1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:6FF1C5AC,-E652-4E94-8CF5-84D52A8E5C15 error: max retries exceeded
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"f8fBVEQmQXDgrrKCU3Xts8nq4F8WXSMf","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'f8fBVEQmQXDgrrKCU3Xts8nq4F8WXSMf', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2B7CA6F7-3F9F-4284-8D14-32237A26476F (syncValue: pCCj166,aUYXjgJ4LRMFpT7v2VEwf678j)'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B7CA6F7-3F9F,-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6FF1C5AC-E652-4E94-8CF5-84D52A8E5C15:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C
[ThaliCore] Advertiser: session connected Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C
,[ThaliCore] Session.session(_:peer:didChange:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C
[ThaliCore] Session.startOutputStream(with:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 4, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-18 09:52:19 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeSt,reams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [2, 4]
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2B7CA6F7,-3F9F-4284-8D14-32237A26476F error: max retries exceeded
2017-07-18 09:52:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pCCj166aUYXjgJ4LRMFpT7v2VEwf678j","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pCCj166aUYXjgJ4LRMFpT7v2VEwf678j', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:19 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"2B7CA6F7-3F9F-4284-8D14-32237A26476F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2B7CA6F7-3F9F-4284-8D14-32237A26476F","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85ED1FFD-D50E-497A-9762-800969B8B575 (syncValue: YpYiACt,6dCADLwT5dhh5JmnJEEGEJHSC)'
2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85ED1FFD-D50E,-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserRelay.deinit
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
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,5ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85,ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:85ED1FFD,-D50E-497A-9762-800969B8B575 error: max retries exceeded
2017-07-18 09:52:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YpYiACt6dCADLwT5dhh5JmnJEEGEJHSC","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YpYiACt6dCADLwT5dhh5JmnJEEGEJHSC', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:24 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:52:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 74EEA8D0-8560-4241-8408-D752D9A14577 (syncValue: hhKsRLf,tcO5temvAIznw8iMISyOrDDr9)'
2017-07-18 09:52:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:74EEA8D0-8560,-4241-8408-D752D9A14577:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:52:24 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-18 09:52:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:74EEA8D0-8560-4241-8408-D752D9A14577:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:74EEA8D0-8560-4241-8408-D752D9A14577:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52601
2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hhKsRLftcO5temvAIznw8iMISyOrDDr9",,"error":null,"portNumber":52601}'
2017-07-18 09:52:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hhKsRLftcO5temvAIznw8iMISyOrDDr9', error: 'null', listeningPort: '52601''
,Connecting to the localhost:52601
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 4, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:52601
2017-07-18 09:52:27 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-18 09:52:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [2, 4]
,2017-07-18 09:52:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeni,ngForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7DE26A7A-5E15-49DC-9309-AE715C12E4A1
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:74EEA8D0-8560-4241-8408-D752D9A14577
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52601
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:74EEA8D0-8560-4241-8408-D752D9A14577:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "74EEA8D0-8560-4241-8408-D752D9A14577", generation: 0)
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hhKsRLftcO5temvAIznw8iMISyOrDDr9","error":"Session disconnected","portNumber":null}'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"74EEA8D0-8560-4241-8408-D752D9A14577","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"74EEA8D0-8560-4241-8408-D752D9A14577","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:74EEA8D0-8560-4241-8408-D752D9A14577:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7DE26A7A-5E15-49DC-9309-AE715C12E4A1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:90B1E51C-01AE-484B-87D1-88A0EBDD303C
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9
,2017-07-18 09:52:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:743EFA39-C137-4C21-B82D-A08FD24,C5A3B
[ThaliCore] Browser.startListening
,2017-07-18 09:52:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:52:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-18 09:52:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
,2017-07-18 09:52:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","generation":0}'
,2017-07-18 09:52:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85ED1FFD-D50E-497A-9762-800969B8B575 (syncValue: FxDAfoT6KRh0OlOMatlbyrPdGUJoXgTf)'
,2017-07-18 09:52:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85,ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2B7CA6F7-3F9F-4284-8D14-32237A26476F","generation":0}'
2017-07-18 09:52:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
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
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
2017-07-18 09:52:31 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA7FABF7-B03B-465A-91E3-B2E4B0213751","generation":0}'
2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:31 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA
[ThaliCore] Advertiser: session connected Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:74526F95-007E-4B61-843A-4180389BA28D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
,2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"74526F95-007E-4B61-843A-4180389BA28D","generation":0}'
2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023
[ThaliCore] Advertiser: session connected Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,5ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2B7CA6F7-3F9F-4284-8D14-32237A26476F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2B7CA6F7-3F9F-4284-8D14-32237A26476F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,5ED1FFD-D50E-497A-9762-800969B8B575", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA
,[ThaliCore] Session.session(_:peer:didChange:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA state: connecting -> connected
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023
,[ThaliCore] Session.session(_:peer:didChange:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA
[ThaliCore] Session.startOutputStream(with:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [2, 4, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:85ED1FFD-D50E-497A-9762-800969B8B575:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:85,ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "85ED1FFD-D50E-497A-9762-800969B8B575", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:85ED1FFD,-D50E-497A-9762-800969B8B575 error: max retries exceeded
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023
[ThaliCore] Session.startOutputStream(with:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023
[Thali,Core] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 4, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
2017-07-18 09:52:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FxDAfoT6KRh0OlOMatlbyrPdGUJoXgTf","er,r,or":"Connection could not be established","portNumber":null}'
2017-07-18 09:52:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FxDAfoT6KRh0OlOMatlbyrPdGUJoXgTf', error: 'Connection could not be established', listeningPort: '%,s''
2017-07-18 09:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969B8B575","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:34 - DEBUG thali,MobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-18 09:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"85ED1FFD-D50E-497A-9762-800969,B8B575","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:52:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] TCPClient: didConnectToHost, active co,nnections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:52:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:52:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA7FABF7-B03B-465A-91E3-B2E4B0213751 (syncValue: F5j6SXwud0Ee61UUbQhcrXAokYlXhLUY)'
,2017-07-18 09:52:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
[ThaliCore] Session.deinit peer:85ED1FFD-D50E-497A-9762-800969B8B575:0
[ThaliCore] BrowserRelay.deinit
2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (5759 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (2097 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received (65536 bytes):'
,2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-18 09:52:34 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:10 [2, 4, 11]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [2, 4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client ,disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52616
2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"F5j6SXwud0Ee61UUbQhcrXAokYlXhLUY",,"error":null,"portNumber":52616}'
2017-07-18 09:52:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'F5j6SXwud0Ee61UUbQhcrXAokYlXhLUY', error: 'null', listeningPort: '52616''
,Connecting to the localhost:52616
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
Connected to the localh,ost:52616
,2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-07-18 09:52:37 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 4, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 124 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [2, 4]
,# teardown
,2017-07-18 09:52:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52616
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
,[ThaliCore] Session.deinit peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7AC678C2-E2C0-4B08-84DE-137EDA7B2023
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.session(_:peer:didChange:) peer:AC3D4257-C08F-462D-A0BC-995CEF73E1AA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "14BBCBC7-F1A6-4ACD-9889-3E919E85D2D9", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6E852978-2FF4-4ED1-9C0A-6D302F43FC0E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6E852978-2FF4-4ED1-9C0A-6D302F43FC0E
2017-07-18 0,9:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 127 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:936BE112-60B4-4C1B-B2DD-9C323660D713
[ThaliCore] Browser.startListening
2017-07,-,18 09:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:52:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 128 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:74526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
[ThaliCore] AdvertiserManager,.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6E852978-2FF4-4ED1-9C0A-6D302F43FC0E
2017-07-18 09:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
201,7-07-18 09:52:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret",:null,"networkType":null}})'
,2017-07-18 09:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-18 09:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 130 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in tea,rdown
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-18 09:52:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 133 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 134 Should be able to call stopAdvertisingAndListening in teardown
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:79F18708-F597-44CD-8EE0-8211850CBE53
[ThaliCore] Browser.startListening
,ok 135 discoveryActive should be false
ok 136 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "028A7DE0-7CDC-4BAC-ABCF-30644F258337", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:028A7DE0-7CDC-4BAC-ABCF-30644F258337
ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 139 d,iscoveryActive should be false
ok 140 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:028A7DE0-7CDC-4BAC-ABCF-30644F258337
ok 141 discoveryActive should be false
ok 142 a,dvertisingActive should be true
ok 143 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
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
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-18 09:52:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-18 09:52:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-18 09:52:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-18 09:52:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-18 09:52:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 156 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 158 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8bc7fc30-6ddb-422d-ba62-1bd9d873ae00 error: startListeningNotActive
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"0XKuL52yNdTZ4VH0DESNRrhSN5c0SNpX","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 159 Should only get called after multiConnect returned
ok 160 SyncValue matches
ok 161 Got right error
ok 162 listeningPort ,is null
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8bc7fc30-6ddb-422d-ba62-1bd9d873ae00","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:48 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8bc7fc30-6ddb-422d-ba62-1,b,d9d873ae00","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:52:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:52:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5280487D-7425-4E23-A4C9-F3CBA68B111B
[ThaliCore] Browser.startListening
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:52:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 165 No error on starting
ok 166 Got null as expected
2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IXJuhTCxXtXWrBfsbHpX797et5ApcJYb","error":"Illegal peerID","portNumber",:null}'
ok 167 Should only get called after multiConnect returned
ok 168 SyncValue matches
ok 169 Got right error
ok 170 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
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
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:52:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42AD419E-539B-4A18-8870-F8624540B90C
[ThaliCore] Browser.startListening
,2017-07-18 09:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 175 No error on starting
ok 176 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18, 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 177 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:51 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 178 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:52:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:52:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 179 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 180 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:344596ca-fa4b-4cb0-9182-cbc50cb38380
ok 182 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 184 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B68E1B2B-5D40-46BE-92E9-A865509D6EEF
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:52:52, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 185 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3884C98-5994-46DF-9BA5-63F3828DDE2F
[ThaliCore] Browser.startListening
2017-07-18 09:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-18 09:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 186 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:74526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
2017-07-18 09:52:52 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"624396A9-3501-4E23-BC49-2F10FDE3AE33","generation":0}'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 624396A9-3501-4E23-BC49-2F10FDE3AE33 (syncValue: bT7R4HVX9bm0NV334YiaHboiLRYhzXJB)'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62,4396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"74526F95-007E-4B61-843A-4180389BA28D","generation":0}'
,2017-07-18 09:52:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,4396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,24396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B68E1B2B-5D40-46BE-92E9-A865509D6EEF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
,[ThaliCore] Session.deinit peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"730E3CE2-CE3F-4684-B97C-85BAE4444C28","generation":0}'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EE1ADE94-333C-449C-BB6D-D3402DE39710:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EE1ADE94-333C-449C-BB6D-D3402DE39710", generation: 0)
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EE1ADE94-333C-449C-BB6D-D3402DE39710","generation":0}'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB
[ThaliCore] Advertiser: session connected Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,4396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,24396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,4396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,24396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB
,[ThaliCore] Session.session(_:peer:didChange:) peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,4396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "624396A9-3501-4E23-BC49-2F10FDE3AE33", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:624396A9,-3501-4E23-BC49-2F10FDE3AE33 error: max retries exceeded
2017-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bT7R4HVX9bm0NV334YiaHboiLRYhzXJB","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bT7R4HVX9bm0NV334YiaHboiLRYhzXJB', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"624396A9-3501-4E23-BC49-2F10FDE3AE33","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"624396A9-3501-4E23-BC49-2F10FDE3AE33","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-18 09:52:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-18 09:52:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2,017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 74526F95-007E-4B61-843A-4180389BA28D (syncValue: ao3a6pxh1Q9omZo7rSAhtj8MxH3TRZUj)'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,h,aliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "74526,F95-007E-4B61-843A-4180389BA28D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:74526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] T,CPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:57 - DEBUG thaliM,obileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:624396A9-3501-4E23-BC49-2F10FDE3AE33:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA7FABF7-B03B-465A-91E3-B2E4B0213751:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA7FABF7-B03B-465A-91E3-B2E4B0213751", generation: 0)
2017-07-18 09:52:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA7FABF7-B03B-465A-91E3-B2E4B0213751","generation":0}'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:57 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:52:57 - DEBUG thaliMobileNativeTestU,tils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:74526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:74526F95-007E-4B61-843A-4180389BA28D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:74,526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,4526F95-007E-4B61-843A-4180389BA28D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "74526F95-007E-4B61-843A-4180389BA28D", generation: 0)
[ThaliCore] Session.session(_:didRece,ive:withName:fromPeer:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB
[ThaliCore] Session.startOutputStream(with:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 4, 13]
[ThaliCore] TCPClient.,c,onnectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ao3a6pxh1Q9omZo7rSAhtj8MxH3TRZUj","error":"Peer is unavailable","portNumber":null}'
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ao3a6pxh1Q9omZo7rSAhtj8MxH3TRZUj', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"74526F95-007E-4B61-843A-4180389BA28D","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"74526F95-007E-4B61-843A-4180389BA28D","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:52:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 730E3CE2-CE3F-4684-B97C-85BAE4444C28 (syncValue: zJQE0itzvRnC9ASMfDzwsnTRgeSPtMdp)'
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:52:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:74526F95-007E-4B61-843A-4180389BA28D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52643
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zJQE0itzvRnC9ASMfDzwsnTRgeSPtMdp",,"error":null,"portNumber":52643}'
2017-07-18 09:53:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zJQE0itzvRnC9ASMfDzwsnTRgeSPtMdp', error: 'null', listeningPort: '52643''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
ok 187 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) found active relay
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MniryD0RZuy5H1UdX3z992dkdHFAjDE,y","error":null,"portNumber":52643}'
,ok 188 No error
,ok 189 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
ok 190 Got null as expected
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [2, 4, 13, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) found active relay
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0l4ldE2ThPLjbB3w26XaXmCAVz95DaZQ","error":null,"portNumber":52643}'
,ok 191 No error
,ok 192 Ports equal
,# teardown
,2017-07-18 09:53:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 193 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B68E1B2B-5D40-46BE-92E9-A865509D6EEF
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,o,nTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 194 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] T,CPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserManager.di,sconnect peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:fal,se
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52643
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] VirtualSocket.cl,o,seStreams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler sta,te:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] Session.disconnect() peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] VirtualSocket.d,einit vsID:14 [2, 4, 13]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] Session.deinit peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,[ThaliCore] TCPListener.deinit
[ThaliCore] VirtualSocket.deinit vsID:13 [2, 4]
,[ThaliCore] BrowserRelay.deinit
2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B68E1B2B-5D40-46BE-92E9-A865509D6EEF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:962A700D-F2C6-4EDA-8A1C-AB673D17DADB
,# initial peer discovery
,2017-07-18 09:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-18 09:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-18 09:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-18 09:53:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'listening 52646'
ok 195 Should throw
,# teardown
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:04 - DEBUG createNativeListener: 'listening 52648'
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 196 initial connection state should be CONNECTED
,2017-07-18 09:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 197 final connection state should be DISCONNECTED
,# teardown
,2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'listening 52651'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 198 tried to connect to right port
ok 199 failed due to refused connection
,ok 200 routerPortConnectionFailed is emitted
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
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'listening 52655'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 201 Send/recvd #1 should be equal length
,ok 202 Send/recvd #1 should be same
,ok 203 Send/recvd #2 should be equal length
,ok 204 Send/recvd #2 should be same
,ok 205 Should be exactly 2 client sockets
,# teardown
,2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'Native Server - close'
2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-18 09:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 52660'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 206 socket shouldn't close until after stream
,ok 207 incoming remains open
,# teardown
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 52664'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 208 we should not have gotten an error
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 209 socket shouldn't close until after incoming
,ok 210 incoming is cleaned up
,# teardown
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 52668'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 211 stream was closed
ok 212 incoming should survive
ok 213 mux should have no streams
,# teardown
,2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'listening 52672'
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 214 we should not have gotten an error
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 215 Buffers are identical
2017-07-18 09:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'Native Server - close'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-18 09:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 216 native server is nulled out
ok 217 native server should be cl,osed
ok 218 incoming has been removed
ok 219 Incoming should be done
ok 220 The mux object should be closed
ok 221 The mux stream should be closed
2017-07-18 09:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection ,<-> Mux - 0 - close'
,# teardown
,2017-07-18 09:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:07 - DEBUG createNativeListener: 'listening 52676'
,2017-07-18 09:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-18 09:53:07 - DEBUG createNativeListener: 'incom,ing - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-18 09:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-07-18 09:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
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
,ok 222 native server is nulled out
,ok 223 native server should be closed
,ok 224 incoming has been removed
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
,2017-07-18 09:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'listening 52728'
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 225 we should not have gotten an error
,2017-07-18 09:53:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 226 Buffers are identical
2017-07-18 09:53:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-18 09:53:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 227 server should be fine
ok 228 server should be open
ok 229 incoming has been removed
ok 230 The mux object should be clos,ed
ok 231 The mux stream should be closed
2017-07-18 09:53:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'listening 52732'
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 232 we should not have gotten an error
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 233 Buffers are identical
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-18 09:53:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-18 09:53:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-18 09:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 234 server should be fine
ok 235 server should be open
ok 236 incoming has been removed
ok 237 The mux object should be closed
ok 238 The mux stream should be closed
,# teardown
,2017-07-18 09:53:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 239 serversManager must not be null
ok 240 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 241 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 52735'
ok 242 port must be in range
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 52736'
ok 243 second start should return same port
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'listening 52738'
,2017-07-18 09:53:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 244 we should be connected
2017-07-18 09:53:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 245 now we are disconnected
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-18 09:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-18 09:53:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 246 Passed bogus id
2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 247 Passed good id but bogus port
2017-07-18 09:53:10 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 248 Passed right context
ok 249 Right server
ok 250 No error should be set
ok 251 Ret,ry should be false
ok 252 We called close server
,# teardown
,# setup
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single local http request
,listening on 52740
,ok 253 should be equal
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B77BB749-103B-4479-A004-5B3078040F60
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 254 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4A18A990-740D-42E7-BA6C-24B16A8EFA4A
[ThaliCore] Browser.startListening
,2017-07-18 09:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 255 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:960D2F62-7D6D-4B13-B832-850740724523:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0)
2017-07-18 09:53:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"960D2F62-7D6D-4B13-B832-850740724523","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 960D2F62-7D6D-4B13-B832-850740724523 (syncValue: 4m1XyPWg7lpOuo9pHfXXChukdZFmngn0)'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:960D2F62-7D6D-4B13-B832-850740724523:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"730E3CE2-CE3F-4684-B97C-85BAE4444C28","generation":0}'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:960D2F62-7D6D-4B13-B832-850740724523:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":0}'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-18 09:53:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:960D2F62-7D6D-4B13-B832-850740724523:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:96,0D2F62-7D6D-4B13-B832-850740724523:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "960D2F62-7D6D-4B13-B832-850740724523", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:960D2F62,-7D6D-4B13-B832-850740724523 error: peer is unavailable
2017-07-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4m1XyPWg7lpOuo9pHfXXChukdZFmngn0","error":"Peer is unavailable","portNumber":null}'
2017-07-18 09:53:13 - D,EBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4m1XyPWg7lpOuo9pHfXXChukdZFmngn0', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event ,with {"peerIdentifier":"960D2F62-7D6D-4B13-B832-850740724523","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
2017-07-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"960D2F62-7D6D-4B13-B832-850740724523","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:53:13 - DEBUG thaliM,obileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:53:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-18 09:53:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 730E3CE2-CE3F-4684-B97C-85BAE4444C28 (syncValue: aR8i00HtxjUIEntuTw47NOP,1BG6AB8xj)'
2017-07-18 09:53:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:730E3CE2-CE3F-4684-B97C-85BAE,4444C28:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:53:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 ,0,9:53:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:960D2F62-7D6D-4B13-B832-850740724523:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,0E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,30E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EE1ADE94-333C-449C-BB6D-D3402DE39710:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EE1ADE94-333C-449C-BB6D-D3402DE39710", generation: 0)
2017-07-18 09:53:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EE1ADE94-333C-449C-BB6D-D3402DE39710","generation":0}'
2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:53:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:53:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] Advertiser: session connected Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
[ThaliCore] Advertiser: session connected Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,0E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,30E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,0E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,30E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EE1ADE94-333C-449C-BB6D-D3402DE39710:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EE1ADE94-333C-449C-BB6D-D3402DE39710", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
,[ThaliCore] Session.session(_:peer:didChange:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28 error: max retries exceeded
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aR8i00HtxjUIEntuTw47NOP1BG6AB8xj","error":"Connection could not be established","portNumber":null}'
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aR8i00HtxjUIEntuTw47NOP1BG6AB8xj', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"730E3CE2-CE3F-4684-B97C-85BAE4444C28","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"730E3CE2-CE3F-4684-B97C-85BAE4444C28","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-18 09:53:18 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E3D0BB5-4FA3-4194-9297-87098529DE9A (syncValue: tpBZsTIF07iTtPXjyYalcIzxGks9JwCm)'
,2017-07-18 09:53:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-18 09:53:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:53:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:730E3CE2-CE3F-4684-B97C-85BAE4444C28:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "730E3CE2-CE3F-4684-B97C-85BAE4444C28", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52756
,2017-07-18 09:53:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tpBZsTIF07iTtPXjyYalcIzxGks9JwCm","error":null,"portNumber":52756}'
,2017-07-18 09:53:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tpBZsTIF07iTtPXjyYalcIzxGks9JwCm', error: 'null', listeningPort: '52756''
,ok 256 should be equal
,2017-07-18 09:53:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6058E2A4-FAC9-450F-81D5-E68925F48B59 (syncValue: bErG8XMSCCgiJQZAKXKAy9qMOS9HAfQn)'
,2017-07-18 09:53:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52760
2017-07-18 09:53:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bErG8XMSCCgiJQZAKXKAy9qMOS9HAfQn",,"error":null,"portNumber":52760}'
2017-07-18 09:53:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bErG8XMSCCgiJQZAKXKAy9qMOS9HAfQn', error: 'null', listeningPort: '52760''
,ok 257 should be equal
# teardown
,[ThaliCore] BrowserManager.disconnect peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52756
[ThaliCore] Session.disconnect() peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:6058E2A4-FAC9-450F-81D5-E68925F48B59
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:52760
[ThaliCore] Session.disconnect() peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:0
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:53:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 0)
,[ThaliCore] Session.deinit peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple local http requests
,listening on 52762
,ok 258 should be equal
ok 259 should be equal
ok 260 should be equal
# teardown
,2017-07-18 09:53:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:B77BB749-103B-4479-A004-5B3078040F60
2017-07-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:26 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType,":null}})'
2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 261 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-0,7-18 09:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not, ,match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdat,e (was in stopped state).'
ok 262 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
2017-07-18 09:53:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","generation":1}'
2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6058E2A4-FAC9-450F-81D5-E68925F48B59, (syncValue: lOddvLYZt2wwhcuNYGdIOeX38yYSww5q)'
2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F,48B59", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
2017-07-18 09:53:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
,2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-18 09:53:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B77BB749-103B-4479-A004-5B3078040F60:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52769
2017-07-18 09:53:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lOddvLYZt2wwhcuNYGdIOeX38yYSww5q",,"error":null,"portNumber":52769}'
2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lOddvLYZt2wwhcuNYGdIOeX38yYSww5q', error: 'null', listeningPort: '52769''
,ok 263 should be equal
ok 264 should be equal
ok 265 should be equal
2017-07-18 09:53:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E3D0BB5-4FA3-4194-9297-87098529DE9A (syncValue: Knxx00rOGhVUjgUBVblaLJqvYRv2phZp)'
2017-07-18 09:53:,30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser,Relay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
[ThaliCore] Advertiser: session connected Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] Advertiser: session connected Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52775
,2017-07-18 09:53:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Knxx00rOGhVUjgUBVblaLJqvYRv2phZp","error":null,"portNumber":52775}'
,2017-07-18 09:53:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Knxx00rOGhVUjgUBVblaLJqvYRv2phZp', error: 'null', listeningPort: '52775''
,ok 266 should be equal
,ok 267 should be equal
,ok 268 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:6058E2A4-FAC9-450F-81D5-E68925F48B59
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52769
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "6058E2A4-FAC9-450F-81D5-E68925F48B59", generation: 1)
,[ThaliCore] BrowserManager.disconnect peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52775
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:B546392C-361E-4C9D-A82C-AFF4F7F58FAB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B77BB749-103B-4479-A004-5B3078040F60", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
2017-07-18 09:53:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lOddvLYZt2wwhcuNYGdIOeX38yYSww5q","error":"Session disconnected","portNumber":null}'
2017-07-18 09:53:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availabili,ty changed event with {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:53:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not bei,ng in started state'
2017-07-18 09:53:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6058E2A4-FAC9-450F-81D5-E68925F48B59","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:53:,34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:2B78F9C9-6BBF-47B1-8B50-629FB064FBE3
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:6058E2A4-FAC9-450F-81D5-E68925F48B59:1
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 269 specific error should be returned
,# teardown
,ok 270 must be stopped
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 271 specific error should be returned
,# teardown
,ok 272 must be stopped
,2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 52779'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 273 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B77BB749-103B-4479-A004-5B3078040F60
[ThaliCore] Advertiser.stopAdvertising() peerID:B77BB749-103B-4479-A004-5B3078040F60
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-18 09:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 275 must be stopped
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 52780'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:32F8394D-3AFC-4E47-8DED-0681AEFC2BD1
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 276 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertis,i,ngActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 277 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
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
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 52781'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "212BDC13-CE81-4D0D-A11F-52AAF9D32DCC", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:212BDC13-CE81-4D0D-A11F-52AAF9D32DCC
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:5,3:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 279 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "212BDC13-CE81-4D0D-A11F-52AAF9D32DCC", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:212BDC13-CE81-4D0D-A11F-52AAF9D32DCC
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-0,7-18 09:53:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 280 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:212BDC13-CE81-4D0D-A11F-52AAF9D32DCC
[ThaliCore] Advertiser.stopAdvertising() peerID:212BDC13-CE81-4D0D-A11F-52AAF9D32DCC
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 must be stopped
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
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 52784'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 282 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 283 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 284 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 285 network status should have certain non-empty properties
,# teardown
,ok 286 must be stopped
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-18 09:53:38 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 287 specific error expected
,# teardown
,ok 288 must be stopped
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 52785'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:06B5545C-28F8-4E85-879C-85A9019179BE
[ThaliCore] Browser.startListening
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D3DFED0-46AB-4D53-885E-D07D512E43A6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:,4D3DFED0-46AB-4D53-885E-D07D512E43A6
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 289 all connection succeed
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}]'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4D3DFED0-46AB-4D53-885E-D07D512E43A6
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 290 must be stopped
2017-07-18 09:53:38 - DEBUG thaliMobile,NativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method m,ultiConnectResolved registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 52788'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:65A2292D-DD86-47FB-8F69-F39C13DB3C9F
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "293DD682-620F-4A52-AB6B-2C952FF9B3F7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:293DD682-620F-4A52-AB6B-2C952FF9B3F7
2017-07-18 09:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 291 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:293DD682-620F-4A52-AB6B-2C952FF9B3F7
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-18 09:53:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 292 must be stopped
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobil,eNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'listening 52790'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9F7496E2-ACFC-4BB4-AAD5-C1420288D6D1
,[ThaliCore] Browser.startListening
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A55120BE-C312-48D1-B0BA-103A58F89DE9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A55120BE-C312-48D1-B0BA-103A58F89DE9
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A55120BE-C312-4,8D1-B0BA-103A58F89DE9
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 293 is stopped after calling stop
,ok 294 connection should fail after stopping
,# teardown
,ok 295 must be stopped
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
,ok 296 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 297 error description matches
,# teardown
,ok 298 must be stopped
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:39 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-18 09:53:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 299 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 300 error description matches
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
,# make sure we actually call kill connections properly
,ok 302 IMPLEMENT ME!!!!!!
,# teardown
,ok 303 must be stopped
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-18 09:53:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
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
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 305 must be stopped
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-18 09:53:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 306 must be stopped
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
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 308 NOT IMPLEMENTED # SKIP
,# teardown
,ok 309 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-18 09:53:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 310 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-18 09:53:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 311 must be stopped
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-18 09:53:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 312 must be stopped
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-18 09:53:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 313 must be stopped
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 52794'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5E93E7EC-56DE-4CF2-B70A-389FCF2D43D6
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 314 discoveryActive matches
ok 315 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 316 discoveryActive matches
ok 317 advertisingActive matches
2017-07-18 09:53:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 52795'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DE2D8EA9-9A79-422B-B8AE-970436E725B4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DE2D8EA9-9A79-422B-B8AE-970436E725B4
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-18 09:53:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 318 discoveryActive matches
,ok 319 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DE2D8EA9-9A79-422B-B8AE-970436E725B4
2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,onTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 320 discoveryActive matches
ok 321 advertisingActive matches
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:53:43 - DEBUG thaliMobileNativeWrapper: 'listening 52797'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 322 must be stopped
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:53:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'listening 52798'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:36F24D70-CFF4-44B8-8A6B-B6F6CAD1AA15
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "123BA6C8-A3D1-4AE1-9949-768227BA748D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,123BA6C8-A3D1-4AE1-9949-768227BA748D
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:44 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-41,94-9297-87098529DE9A","generation":0}]'
2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}]'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 323 portNumber equal null
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:123BA6C8-A3D1-4AE1-9949-768227BA748D
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 324 must be stopped
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
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'listening 52800'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2AC0534B-6146-4457-9AB7-38E4FCF84D7D
[ThaliCore] Browser.startListening
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF
,2017-07-18 09:53:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:53:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-18 09:53:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}]'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:), found peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}]'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}]'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E3D0BB5-4FA3-4194-9297-87098529DE9A (syncValue: MahUMBCj4atMUl3KHYDxo1dxPr1B5FeO)'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null}'
2017-07-18 09:53:46 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}]'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}'
,2017-07-18 09:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:53:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7E3D0BB5,-4FA3-4194-9297-87098529DE9A error: max retries exceeded
2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MahUMBCj4atMUl3KHYDxo1dxPr1B5FeO","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:53:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MahUMBCj4atMUl3KHYDxo1dxPr1B5FeO', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:53:50 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:53:50 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null,"recreated":true}'
2017-07-18 09:53:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
2017-07-18 09:53:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":true,"generation":1,"portNumber":null,"recreated":true}'
2017-07-18 09:53:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:53:50 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3 (syncValue: qNrMFHIG2qjHHy1eLn3PW4F7BJz9VPEI)'
2017-07-18 09:53:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-A,C7071FDF7A3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h,:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7E3D0BB5-4FA3-4194-9297-87098529DE9A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:7E3D0BB5-4FA3-4194-9297-87098529DE9A:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7E3D0BB5-4FA3-4194-9297-87098529DE9A", generation: 1)
2017-07-18 09:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}]'
2017-07-18 09:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"7E3,D0BB5-4FA3-4194-9297-87098529DE9A","generation":1}'
,2017-07-18 09:53:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-18 09:53:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7E3D0BB5-4FA3-4194-9297-87098529DE9A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52812
2017-07-18 09:53:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qNrMFHIG2qjHHy1eLn3PW4F7BJz9VPEI",,"error":null,"portNumber":52812}'
2017-07-18 09:53:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qNrMFHIG2qjHHy1eLn3PW4F7BJz9VPEI', error: 'null', listeningPort: '52812''
,2017-07-18 09:53:53 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 4, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:53:53 - DEBUG testUtils: 'Got response data'
2017-07-18 09:53:53 - DEBUG testUtils: 'Got end'
ok 325 response body should match testData
ok 326 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F80E614C-89F2-4E6B-9BBB-DD598F1E5ADF
2017-07-18 09:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:53:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-18 09:53:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 327 must be stopped
[ThaliCore] BrowserManager.disconnect peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3
[ThaliCore] BrowserRelay.closeRelay() state:connected,
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52812
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDi,dDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:,disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] Session.disconnect() peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler st,ate:disconnecting
[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] VirtualSocket.deinit vsID:15 [2, 4]
[ThaliCore] TCPListener.deinit
[ThaliCore] BrowserRelay.deinit
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'listening 52814'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D5B38585-3AFA-4187-8B9C-9F83CD736B33
[ThaliCore] Browser.st,artListening
2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,CA048616-D84D-433B-A13F-489E42F417AC
,2017-07-18 09:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-18 09:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}]'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
2017-07-18 09:53:55 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3 (syncValue: nxM8mkHZ81T6VUb,3FHG0WmQqU717u33Z)'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BC,E6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChang,ed event from native layer [{"peerAvailable":true,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}]'
2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIde,ntifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A
[ThaliCore] Advertiser: session connected Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:953E254B-C59F-49CE-9D01-EB3331406366:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "953E254B-C59F-49CE-9D01-EB3331406366", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA048616-D84D-433B-A13F-489E42F417AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:832,961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {",peerAvailable":false,"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3BAEA213-54FC-4444-8A5D-A5BD960AADD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:P,eer(uuid: "3BAEA213-54FC-4444-8A5D-A5BD960AADD9", generation: 0)
2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095",,"generation":0}]'
2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}'
,2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","generation":0}]'
2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","generation":0}'
,2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:53:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"953E254B-C59F-49CE-9D01-EB3331406366","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:53:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:53:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A
,[ThaliCore] Session.session(_:peer:didChange:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A
[ThaliCore] Session.startOutputStream(with:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 4, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1F1A54A6,-E12A-4C1D-BCE6-AC7071FDF7A3 error: max retries exceeded
2017-07-18 09:53:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nxM8mkHZ81T6VUb3FHG0WmQqU717u33Z","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:53:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nxM8mkHZ81T6VUb3FHG0WmQqU717u33Z', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:53:59 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:53:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:53:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:53:59 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:53:59 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:53:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:53:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:53:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:53:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 832961D1-12F0-4253-9FBC-B054D32A0095 (syncValue: DF6bphwLPXDfHDEk0nBzCpy4fEtyr1RS)'
2017-07-18 09:53:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "832961D1-12F0-4253-9FBC-B,054D32A0095", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h,:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52831
2017-07-18 09:54:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DF6bphwLPXDfHDEk0nBzCpy4fEtyr1RS",,"error":null,"portNumber":52831}'
2017-07-18 09:54:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DF6bphwLPXDfHDEk0nBzCpy4fEtyr1RS', error: 'null', listeningPort: '52831''
,2017-07-18 09:54:02 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 4, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:54:02 - DEBUG testUtils: 'Got response data'
2017-07-18 09:54:02 - DEBUG testUtils: 'Got end'
ok 328 response body should match testData
ok 329 must be started
# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CA048616-D84D-433B-A13F-489E42F417AC
2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:54:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 330 must be stopped
[ThaliCore] BrowserManager.disconnect peer:832961D1-12F0-4253-9FBC-B054D32A0095
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore], TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52831
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_,:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false soc,ket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] V,irtualSocket exited RunLoop vsID:17
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed vir,tual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] Session.disconnect() peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHand,ler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:17 [2, 4, 16]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] AdvertiserRelay.didCloseVirtu,alSocketStreamsHandler disconnecting:false
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[ThaliCore] VirtualSocket.deinit vsID:16 [2, 4]
2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CA048616-D84D-433B-A13F-489E42F417AC", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:11BCFA4D-5BE1-460C-968F-2F65E7BABE5A
,# calls correct starts when network changes
,2017-07-18 09:54:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 331 must be stopped
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 332 must be stopped
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'listening 52833'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15FFD872-4FA8-4E97-B00D-5F02A41E7915
[ThaliCore] Browser.st,artListening
2017-07-18 09:54:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:54:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:06 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,A2FF3948-3AB1-4483-B3E0-379DCE76812F
2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:54:06 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:06 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
2017-07-18 09:54:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}]'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
2017-07-18 09:54:06 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 832961D1-12F0-4253-9FBC-B054D32A0095 (syncValue: OUVFZt49mQ3nJOD,23C2z31Uv6OR6xNZQ)'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:832961D1-12F0-4253-9F,BC-B054D32A0095:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChang,ed event from native layer [{"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}]'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIde,ntifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}'
,2017-07-18 09:54:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
2017-07-18 09:54:07 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}]'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}'
2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}]'
2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"pe,erAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A2FF3948-3AB1-4483-B3E0-379DCE76812F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A2FF3948-3AB1-4483-B3E0-379DCE76812F", generation: 0)
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:832961D1-12F0-4253-9FBC-B054D32A0095:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:83,2961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:832961D1,-12F0-4253-9FBC-B054D32A0095 error: max retries exceeded
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OUVFZt49mQ3nJOD23C2z31Uv6OR6xNZQ","error":"Connection could not be established","portNumber":null}'
2017-0,7-18 09:54:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OUVFZt49mQ3nJOD23C2z31Uv6OR6xNZQ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:10 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:54:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:54:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-18 09:54:10 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3 (syncValue: OgbOAw4PIFDJEYb5n9QqwSXVbVLFRo84)'
2017-07-18 09:54:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-A,C7071FDF7A3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h,:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:832961D1-12F0-4253-9FBC-B054D32A0095:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "832961D1-12F0-4253-9FBC-B054D32A0095", generation: 0)
2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}]'
2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","generation":0}'
,2017-07-18 09:54:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-18 09:54:11 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"832961D1-12F0-4253-9FBC-B054D32A0095","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
2017-07-18 09:54:12 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}]'
2017-07-18 09:54:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}'
,2017-07-18 09:54:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-18 09:54:12 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:54:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OgbOAw4PIFDJEYb5n9QqwSXVbVLFRo84","error":"Peer is unavailable",,"portNumber":null}'
2017-07-18 09:54:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OgbOAw4PIFDJEYb5n9QqwSXVbVLFRo84', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-18 09:54:13 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:54:13 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:54:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3
2017-07-18 09:54:13 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-18 09:54:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 50E8281F-8162-4C2A-8FC0-78964F5A9464 (syncValue: D9ThpgLIEd0yW9E8QZLu40qhA8HM2hLp)'
2017-07-18 09:54:13 - DEBUG thaliMobileNativeTestUt,ils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:,sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.init(session:generation:crea,teVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3", generation: 0)
,2017-07-18 09:54:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}]'
,2017-07-18 09:54:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","generation":0}'
,2017-07-18 09:54:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-18 09:54:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.deinit peer:1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52853
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"D9ThpgLIEd0yW9E8QZLu40qhA8HM2hLp",,"error":null,"portNumber":52853}'
2017-07-18 09:54:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'D9ThpgLIEd0yW9E8QZLu40qhA8HM2hLp', error: 'null', listeningPort: '52853''
,2017-07-18 09:54:16 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 4, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:54:16 - DEBUG testUtils: 'Got response data'
2017-07-18 09:54:16 - DEBUG testUtils: 'Got end'
ok 333 response body should match testData
ok 334 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A2FF3948-3AB1-4483-B3E0-379DCE76812F
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-18 09:54:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-18 09:54:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 335 must be stopped
[ThaliCore] BrowserManager.disconnect peer:50E8281F-8162-4C2A-8FC0-78964F5A9464
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore], TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52853
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_,:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnectin,g,
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] Session.disconnect() peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnec,ting
[ThaliCore] VirtualSocket.deinit vsID:18 [2, 4]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.deinit
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method pe,erAvailabilityChanged registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-18 09:54:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-18 09:54:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 336 FIX ME, PLEASE!!!
,# teardown
,ok 337 must be stopped
,2017-07-18 09:54:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:54:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-18 09:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 338 must be stopped
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-18 09:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 339 must be stopped
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-18 09:54:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-18 09:54:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-18 09:54:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-18 09:54:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 340 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 341 specific error should be returned
,# teardown
,2017-07-18 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3BAEA213-54FC-4444-8A5D-A5BD960AADD9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:19 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:19 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1F1A54A6-E12A-4C1D-BCE6-AC7071FDF7A3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 342 error should be null
,ok 343 error should be null
,# setup
,ok 344 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 345 specific error should be returned
,# teardown
,ok 346 error should be null
ok 347 error should be null
,# setup
,ok 348 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 52855'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 349 error should be null
ok 350 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 351 error should be null
ok 352 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-18 09:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 353 error should be null
ok 354 error should be null
,# setup
,ok 355 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 52856'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2B04D00-3A45-4FA1-87BC-163897764A78
[ThaliCore] Browser.st,artListening
2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 356 error should be null
ok 357 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 358 error should be null
ok 359 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}]'
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}'
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] Browser.br,owser(_:foundPeer:withDiscoveryInfo:) found peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}]'
2017-07-18 09:54:20 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}'
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 360 error should be null
,ok 361 error should be null
,# setup
,ok 362 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 52857'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "33E5980E-816D-4860-8A47-27F8A888DBE7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:33E5980E-816D-4860-8A47-27F8A888DBE7
2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 363 error should be null
ok 364 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "33E5980E-816D-4860-8A47-27F8A888DBE7", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:33E5980E-816D-4860-8A47-27F8A888DBE7
20,17-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 365 error should be null
ok 366 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:33E5980E-816D-4860-8A47-27F8A888DBE7
,[ThaliCore] Advertiser.stopAdvertising() peerID:33E5980E-816D-4860-8A47-27F8A888DBE7
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 367 error should be null
,ok 368 error should be null
,# setup
,ok 369 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 52860'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 370 error should be null
,ok 371 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 372 error should be null
,ok 373 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 374 error should be null
,ok 375 error should be null
,# setup
,ok 376 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-18 09:54:21 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 377 This should not cause wifi to fail
ok 378 native router should be bad
,# teardown
,ok 379 error should be null
ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-18 09:54:21 - DEBUG thaliMobileNativeWrapper: 'listening 52861'
ok 382 first call should succeed
ok 383 first call should succeed
ok 384 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:22 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-18 09:54:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 385 error should be null
ok 386 error should be null
,# setup
,ok 387 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-18 09:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 388 error should be null
ok 389 error should be null
,# setup
,ok 390 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-18 09:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 391 error should be null
ok 392 error should be null
,# setup
,ok 393 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-18 09:54:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da7f68ad-b3b0-47c4-820b-6116d37d856b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 394 should be calle,d once
ok 395 should not have been called more than once
,# teardown
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"da7f68ad-b3b0-47c4-820b-6116d37d856b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# can get the network status
,ok 399 network status should have certain non-empty properties
,# teardown
,ok 400 error should be null
ok 401 error should be null
,# setup
,ok 402 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 403 we have not added peer to the cache yet
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4e9084cf-236a-4052-b14b-04787a4e7b21","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 404 peer should be ,available
ok 405 cache contains native peer
2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4e9084cf-236a-4052-b14b-04787a4e7b21","connectionType":"MPCF","peerAvailable":false,"generation":0,",newAddressPort":null}'
ok 406 peer should be unavailable
ok 407 peer has been removed from cache
,# teardown
,ok 408 error should be null
ok 409 error should be null
,# setup
,ok 410 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 411 we have not added peer to the cache yet
,2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c8fbf7db-9ed0-46be-bd68-b45127712362","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 412 peer should be a,vailable
ok 413 cache contains wifi peer
2017-07-18 09:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c8fbf7db-9ed0-46be-bd68-b45127712362","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 414 peer should be unavailable
ok 415 peer has been removed from cache
,# teardown
,ok 416 error should be null
ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0d0ebe70-4160-4e89-8688-cf5ca9fb4ef9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 419 first peer is available
2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"19154f69-7221-4916-9729-4487b864b9f3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 420 second peer is available
ok 421 first and second peers are different
,# teardown
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0d0ebe70-4160-4e89-8688-cf5ca9fb4ef9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"19154f69-7221-4916-9729-4487b864b9f3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 422 error should be null
ok 423 error should be null
,# setup
,ok 424 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 425 should not be in cache at start
2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8c70ccce-0c66-42de-a061-2557ae0c0e09","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 426 peer is available
,# teardown
,2017-07-18 09:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8c70ccce-0c66-42de-a061-2557ae0c0e09","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 error should be null
ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-18 09:54:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 430 error should be null
ok 431 error should be null
,# setup
,ok 432 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-18 09:54:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 433 error should be null
ok 434 error should be null
,# setup
,ok 435 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd1cb734-13ac-4d2a-859f-ec9349bb0c56","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 436 peer should be available
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd1cb734-13ac-4d2a-859f-ec9349bb0c56","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 437 peer should be available
ok 438 should store correct generation
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dd1cb734-13ac-4d2a-859f-ec9349bb0c56","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 439 error should be null
ok 440 error should be null
,# setup
,ok 441 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'listening 52862'
2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d8bfbf8b-d0e8-4b54-b333-e3ceca050ca8","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 442 discovered correct peer
ok 443 got correct generation
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d8bfbf8b-d0e8-4b54-b333-e3ceca050ca8","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 444 discovered corr,ect peer
ok 445 got correct generation
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d8bfbf8b-d0e8-4b54-b333-e3ceca050ca8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 446 error should be null
ok 447 error should be null
,# setup
,ok 448 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'listening 52863'
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a57f0c55-b414-4812-873d-5c9d2cf8b3d8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 449 discovered avai,lable peer
ok 450 peer is available
,# teardown
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a57f0c55-b414-4812-873d-5c9d2cf8b3d8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 451 error should be null
ok 452 error should be null
,# setup
,ok 453 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"81f04a60-e7cb-4d36-9e3d-cd6f4ca463e6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 454 peer should be ,available
2017-07-18 09:54:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"81f04a60-e7cb-4d36-9e3d-cd6f4ca463e6","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 455 peer, should be unavailable
ok 456 should be removed from cache
,# teardown
,ok 457 error should be null
ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 52864'
2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8af94220-7771-4cb0-9406-ba67878d6c91","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 460 first peer is expected to be available
2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"041eee48-e68e-47d4-8079-7e9c49b43650","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 461 second peer is expected to be available
2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"041eee48-e68e-,47d4-8079-7e9c49b43650","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 462 peer became unavailable
ok 463 it was wifi peer
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"041eee48-e68e-47d4-8079-7e9c49b43650","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 464 we found peer ag,ain
ok 465 it was wifi peer
2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"041eee48-e68e-47d4-8079-7e9c49b43650","connectionType":"tcp","peerAvailable":false,"generation":null,"newAd,dressPort":null}'
,ok 466 peer became unavailable
,ok 467 it was wifi peer
,# teardown
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8af94220-7771-4cb0-9406-ba67878d6c91","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:26 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 468 error should be null
ok 469 error should be null
,# setup
,ok 470 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 52865'
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ae8a380-4e7f-4eda-8d24-10b6f46ea451","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 first peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07445d0d-a750-4fdf-aff4-7a461939a69a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 475 second peer is expected to be available
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5ae8a380-4e7f-4eda-8d24-10b6f46ea451","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 476 peer became unavailable
,2017-07-18 09:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"07445d0d-a750-4fdf-aff4-7a461939a69a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 477 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:26 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 481 error should be null
ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-18 09:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 484 error should be null
,ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fc8efd41-1e88-4e17-a82a-f981f2832d39","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 487 peer discovered ,first time does not have new address
2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fc8efd41-1e88-4e17-a82a-f981f2832d39","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 488 address has not been changed
,2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fc8efd41-1e88-4e17-a82a-f981f2832d39","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 489 new port handled, correctly
2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fc8efd41-1e88-4e17-a82a-f981f2832d39","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 490 new ,host handled correctly
2017-07-18 09:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fc8efd41-1e88-4e17-a82a-f981f2832d39","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}',
ok 491 newAddressPort is null for unavailable peers
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-18 09:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 498 NOT IMPLEMENTED # SKIP
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-18 09:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 502 error should be null
ok 503 error should be null
,# setup
,ok 504 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 505 should be equal
,# teardown
,ok 506 error should be null
ok 507 error should be null
,# setup
,ok 508 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-18 09:54:28 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 contains expected properties
,ok 513 the same hostAddress
,ok 514 the same portNumber
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 518 contains expected properties
,ok 519 the same hostAddress
,ok 520 the same portNumber
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 521 error should be null
,ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'listening 52866'
2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7ccf8130-5784-456b-98eb-02f22e79377e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 524 Got specific error message
,# teardown
,2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7ccf8130-5784-456b-98eb-02f22e79377e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:29 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-,07-18 09:54:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:54:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 525 error should be null
ok 526 error should be null
,# setup
,ok 527 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-18 09:54:29 - DEBUG thaliMobileNativeWrapper: 'listening 52867'
2017-07-18 09:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"79f17862-ed9a-4d5f-a13f-1463a35df2ba","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:79f17862-ed9a-4d5f-a13f-1463a35df2ba
ok 528 native wrapper `disconnect` called once
ok 529 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-18 09:54:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"79f17862-ed9a-4d5f-a13f-1463a35df2ba","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 530 error should be null
,ok 531 error should be null
,# setup
,ok 532 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 533 error should be null
ok 534 error should be null
,# setup
,ok 535 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 536 error should be null
ok 537 error should be null
,# setup
,ok 538 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 539 error should be null
ok 540 error should be null
,# setup
,ok 541 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-18 09:54:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 542 error should be null
ok 543 error should be null
,# setup
,ok 544 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 545 error should be null
ok 546 error should be null
,# setup
,ok 547 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 548 error should be null
ok 549 error should be null
,# setup
,ok 550 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-18 09:54:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 551 error should be null
ok 552 error should be null
,# setup
,ok 553 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'listening 52868'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E66B0991-1017-4FB5-8194-67713051E524
[ThaliCore] Browser.startListening
2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"389941e9-abbf-443f-b498-8830d45c7cae","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 554 Peer availabili,ties has one entry for our connection type
2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"04fc843e-e7e5-460b-ab5c-50a301bd261b","connectionType":"tcp","peerAvailable":true,"generation":0,"newA,ddressPort":false}'
ok 555 Peer availabilities has one entry for our connection type
2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"389941e9-abbf-443f-b498-8830d45c7cae","connectionT,ype":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"04fc843e-e7e5-460b-ab5c-50a301bd261b","connectionType":"tcp,",,"peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 556 No peers
,ok 557 No peers
,ok 558 No peers
,# teardown
,ok 559 error should be null
ok 560 error should be null
,# setup
,ok 561 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'listening 52869'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05765383-9c4e-484f-9ff5-4879d1d47928","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 562 1
,ok 563 2
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ac19b78-5a3c-4c89-94e0-0cc726a8ebf3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"05765383-9c4e-484f-9ff5-4879d1d47928","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6ac19b78-5a3c-4c89-94e0-0cc726a8ebf3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-18 09:54:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:54:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 564 error should be null
,ok 565 error should be null
,# setup
,ok 566 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-18 09:54:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 567 error should be null
,ok 568 error should be null
,# setup
,ok 569 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'listening 52870'
ok 570 error should be null
ok 571 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "104BF86E-803C-46C8-8A9E-83,87091CD103", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:104BF86E-803C-46C8-8A9E-8387091CD103
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
,ok 572 error should be null
ok 573 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:95A0E461-9F45-4061-BC4B-3B465DD9E1FD
[ThaliCore] Browser.startListening
2,017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 574 error should be null
ok 575 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
2017-07-18 09:54:33 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}]'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}]'
2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:54:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 50E8281F-8162-4C2A-8FC0-78964F5A9464 (syncValue: 0)'
,2017-07-18 09:54:33 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:50,E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,0E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
2017-07-18 09:54:34 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","generation":0}]'
2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","generation":0}'
,2017-07-18 09:54:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:34 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:104BF86E-803C-46C8-8A9E-8387091CD103:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
2017-07-18 09:54:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","generation":0}]'
2017-07-18 09:54:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","generation":0}'
,2017-07-18 09:54:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:54:35 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:50,E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,0E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
[ThaliCore] Advertiser: session connected Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
[ThaliCore] Advertiser: session connected Peer(uuid: "104BF86E-803C-46C8-8A9E-8387091CD103", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:25F94381-7A5C-4103-B229-CF501806E9D4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:50E8281F-8162-4C2A-8FC0-78964F5A9464 error: max retries exceeded
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7715A4C7-4E63-4CF7-ACF2-CA28E269C078 (syncValue: 1)'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:54:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-18 09:54:37 - DEBUG thaliMobile,: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:50E8281F-8162-4C2A-8FC0-78964F5A9464:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}]'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","generation":0}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}]'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","generation":0}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:54:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:54:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-18 09:54:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:77,15A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7715A4C7-4E63-4CF7-ACF2-CA28E269C078", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:54:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unavailable","portNumber":null}'
2017-07-1,8 09:54:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:38 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:54:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1329D8,4C-3DE0-4ED2-9740-36D47DF4B8A6 (syncValue: 2)'
2017-07-18 09:54:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A,6,", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) pee,r:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-18 09:54:38 - DEBUG thaliMobileNativeWrapper: 'handleP,eerUnavailable - Emitting {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:54:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting, {"peerIdentifier":"7715A4C7-4E63-4CF7-ACF2-CA28E269C078","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
,[ThaliCore] Session.session(_:peer:didChange:) peer:25F94381-7A5C-4103-B229-CF501806E9D4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
[ThaliCore] Session.startOutputStream(with:) peer:25F94381-7A5C-4103-B229-CF501806E9D4
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [2, 4, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
[ThaliCore] Session.startOutputStream(with:) peer:3D6A37F7-08ED-4D66-A1B5-D3E4F6D61074
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 4, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1329D84C-3DE0-4ED2-9740-36D47DF4B8A6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52886
2017-07-18 09:54:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":52886,}'
,2017-07-18 09:54:42 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 45ABA631-FD53-4044-BA01-13FE72BF09A5 (syncValue: 3)'
2017-07-18 09:54:42 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1329D84C-3DE0-4ED2-9740-36D47DF4B8A6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 4, 19, 20, 21]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:54:42 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:42 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "45ABA631-FD53-4044-BA01-13FE72BF09A5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52891
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":52891,}'
,2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 50E8281F-8162-4C2A-8FC0-78964F5A9464 (syncValue: 4)'
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Peer is unavailable","portNumber":null}'
2017-07-1,8 09:54:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 50E828,1F-8162-4C2A-8FC0-78964F5A9464 (syncValue: 5)'
,2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "50E8281F-8162-4C2A-8FC0-78964F5A9464", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":"Peer is unavailable","portNumber":null}'
2017-07-1,8 09:54:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:7715A4C7-4E63-4CF7-ACF2-CA28E269C078
2017-,07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-18 09:54:45 - DEBUG thaliMobileNativ,eWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailability,Changed - Emitting {"peerIdentifier":"50E8281F-8162-4C2A-8FC0-78964F5A9464","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:50E8281F-8162-4C2A-8FC0-78964F5A9464
[ThaliCore] BrowserManager.disconnect pe,er:50E8281F-8162-4C2A-8FC0-78964F5A9464
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:45ABA631-FD53-4044-BA01-13FE72BF09A5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 4, 19, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:54:45 - DEBUG testUtils: 'Got response data'
2017-07-18 09:54:45 - DEBUG testUtils: 'Got end'
ok 576 received all uuids
,# teardown
,2017-07-18 09:54:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1329D84C-3DE0-4ED2-9740-36D47DF4B8A6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:54:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45ABA631-FD53-4044-BA01-13FE72BF09A5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:104BF86E-803C-46C8-8A9E-8387091CD103
2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-18 09:54:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-18 09,:54:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:54:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:54:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-18 09:54:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 577 error should be null
,ok 578 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeS,treams() vsID:19
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:20
# setup
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [2, 4, 20, 21, 22]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [2, 4, 21, 22]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [2, 4, 21]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 579 ThaliMobile should be stopped
,# test for data corruption
,2017-07-18 09:54:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 580 error should be null
ok 581 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[Th,aliCore] VirtualSocket.deinit vsID:21 [2, 4]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconne,ctHandler
,# #testThaliPeerAction - test getters
,ok 582 getPeerIdentifier
ok 583 getConnectionType
ok 584 getActionType
,ok 585 getActionState
ok 586 getPskIdentity
ok 587 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 588 initial state
ok 589 after start
2017-07-18 09:54:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 590 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 591 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-18 09:54:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 592 clean kill
ok 593 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 594 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 595 forever agent should have it's own destroy method
,ok 596 agent's destroy should be called
ok 597 agent's destroy should not be called again
ok 598 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 599 Entry counter must be 1
ok 600 Entry exists
ok 601 Size must be 1
ok 602 Entry counter must be 2
ok 603 Entry exists
,ok 604 Size must be 2
,ok 605 Entry counter must be 1
,ok 606 Entry exists
,ok 607 Size must be 3
,ok 608 Entry counter must be 2
,ok 609 Entry exists
,ok 610 Size must be 4
,ok 611 Entry 1_1 should not be found
,ok 612 Entry 1_1 does not exist
,ok 613 Size must be 3
,ok 614 Entry 1_2 should not be found
,ok 615 Entry 1_2 does not exist
,ok 616 Size must be 2
,ok 617 should be equal
,ok 618 Entry 2_1 should not be found
,ok 619 Entry 2_2 should not be found
,ok 620 Entry 2_1 does not exist
,ok 621 Entry 2_2 does not exist
,ok 622 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 623 Size must be100
,ok 624 Entries between 20 and MAXSIZE + 20 should exist
,ok 625 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 626 Entries between 6 and MAXSIZE + 4 should exist
ok 627 Size should be MAXSIZE
,ok 628 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 629 WAITING state entry should not be removed
,ok 630 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 631 Size should be MAXSIZE
,ok 632 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 633 Kill should be called once
ok 634 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 635 is an agent
,ok 636 enqueue is fine
,ok 637 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 638 is an agent
ok 639 first enqueue is fine
ok 640 is an agent
ok 641 second enqueue is fine
ok 642 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 643 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 644 is an agent
ok 645 good enqueue
,ok 646 Identity should match
,2017-07-18 09:54:54 - DEBUG testUtils: 'Got response data'
,2017-07-18 09:54:54 - DEBUG testUtils: 'Got end'
,ok 647 Got expected response
,ok 648 Got psk call back
,# teardown
,2017-07-18 09:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 649 is an agent
ok 650 enqueue worked
,ok 651 is an agent
,ok 652 enqueue 2 worked
,ok 653 enqueue is not available when stopped
,ok 654 start action is killed
,ok 655 killed action is still killed
,ok 656 enqueued action when stopped is killed
,ok 657 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 658 good start
ok 659 good enqueue
,ok 660 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 661 null arg
ok 662 wrong arg type
ok 663 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 664 good enqueue
,ok 665 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 666 good enqueue
ok 667 2nd good enqueue
ok 668 we are in the pool
ok 669 We are out of the pool
ok 670 Action was killed
ok 671 The original kill was called too
ok 672 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 673 good enqueue
ok 674 first kill
,ok 675 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 676 1st good enqueue
ok 677 2nd good enqueue
,ok 678 1st action is in the pool
ok 679 2nd action is in the pool
ok 680 1st action is out of the pool
ok 681 2st action is out of the pool
ok 682 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-18 09:54:57 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 683 Got right error
ok 684 Start should not be called
ok 685 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-18 09:54:57 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-18 09:54:57 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 686 Got right error
,ok 687 Start should not be called
,ok 688 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 689 Got null
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 690 is an agent
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 691 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 692 Got Null
ok 693 Got another null
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 694 is an agent
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 695 is an agent
2017-07-18 09:54:58 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 696 Action 1 killed at least once
,ok 697 Action 1 went first
ok 698 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 699 should have gotten null
2017-07-18 09:54:59 ,- DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 700 Should have stopped nicely
2017-07-18 ,09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 701 Still looking for null
2017-07-18, 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneA,t,ATime: 'Replication action failed badly so we are going to retry'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2017-0,7-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 702 Yup, another null
ok 703 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 704 Null 1
,ok 705 (unnamed assert)
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 706 is an agent
,ok 707 Null 3
,ok 708 Replication not yet called
,ok 709 Notification 2 not yet called
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 710 is an agent
,ok 711 Notification went first
,ok 712 Notification 2 not called yet
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 713 is an agent
,ok 714 Notification finished
,ok 715 Replication finished
,2017-07-18 09:54:59 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 716 is an agent
ok 717 First does not throw
2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 718 is an agent
ok 719 Second does not throw
2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtAT,ime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-18 09:55:00 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 720 is an agent
ok ,721 first ok
2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 722 is an agent
ok 723 second ok
ok 724 third ok
,2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-18 09:55:01 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-18 09:55:01 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-18 09:55:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-18 09:55:01 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 725 peerIdentifier should match
,ok 726 generation should match
,ok 727 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 728 good beacon
,ok 729 good preAmble
,ok 730 public keys match!
,ok 731 must return null after successful call
,ok 732 Once start returns the action should be in KILLED state
,# teardown
,2017-07-18 09:55:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 733 Response should be HTTP_BAD_RESPONSE
,ok 734 must return null after successful call
,# teardown
,2017-07-18 09:55:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 735 Response should be NETWORK_PROBLEM
,ok 736 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-18 09:55:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 737 Resolution should be BAD_PEER
,ok 738 correct error message
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 739 Call start once
,ok 740 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 741 must return null after successful call.
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 742 Should be Killed
,ok 743 Start after killed
,# teardown
,2017-07-18 09:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 744 Should be KILLED
,ok 745 must return null after successful kill
,# teardown
,2017-07-18 09:55:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 746 Should be KILLED
ok 747 must return null after successful kill
,# teardown
,2017-07-18 09:55:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 748 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 749 must return null after successful call
,# teardown
,2017-07-18 09:55:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-18 09:55:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 750 Should be NETWORK_PROBLEM caused closing server socket
ok 751 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 752 Should be NETWORK_PROBLEM caused closing client socket
,ok 753 Should be Could not establish TCP connection
,# teardown
,2017-07-18 09:55:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 754 publicKeysToNotify cannot be null
ok 755 ecdh for local device cannot be null
ok 756 milliseconds cannot be less than 0
ok 757 milliseconds cannot be 0
ok 758 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 759 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 760 should be equal
,ok 761 should be equal
ok 762 (unnamed assert)
,ok 763 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 764 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 765 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 766 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 767 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 768 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 769 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 770 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 771 should be equal
ok 772 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 773 should be equal
,ok 774 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 775 right number of calls to address book
,ok 776 good preAmble
ok 777 good unencryptedKeyId
ok 778 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 779 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 780 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 781 Matching numbers
,ok 782 We have an entry!
ok 783 keys match
,ok 784 secrets match
,ok 785 We have an entry!
,ok 786 keys match
,ok 787 secrets match
,ok 788 We have an entry!
ok 789 keys match
,ok 790 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 791 Streams have same length
,ok 792 matching size
,ok 793 keys match
,ok 794 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 795 should be equal
,ok 796 peerDictionalty contains 2 peers
,ok 797 bluetooth peer's notification has correct connection type
,ok 798 tcp peer's notification has correct connection type
,2017-07-18 09:55:20 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-18 09:55:20 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-18 09:55:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 799 notification peer dictionary contains exactly 1 peer
2017-07-18 09:55:20 - WARN thaliNotificationClient: 'peer is not available'
,ok 800 notification peer dictionary does not contain any peers
,2017-07-18 09:55:20 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-18 09:55:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 801 entry exists
ok 802 entry is resolved
,# teardown
,2017-07-18 09:55:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 803 Action should be KILLED
,ok 804 Peer state should be RESOLVED
,# teardown
,2017-07-18 09:55:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 805 hostAddress must match
,ok 806 portNumber must match
,ok 807 suggestedTCPTimeout must match
,ok 808 connectionType must match
,ok 809 peerIDs must match
,# teardown
,2017-07-18 09:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 810 Correct error
,# teardown
,2017-07-18 09:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 811 hostAddress must match
,ok 812 portNumber must match
,ok 813 suggestedTCPTimeout must match
,ok 814 connectionType must match
,ok 815 peerIds must match
,# teardown
,2017-07-18 09:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-18 09:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 816 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 817 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 818 action should be resolved with NETWORK_PROBLEM error
,2017-07-18 09:55:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 819 action should be resolved with NETWORK_PROBLEM error
ok 820 correct number of requests
ok 821 correct number of failures
ok 822 correct final peer state
,# teardown
,2017-07-18 09:55:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-18 09:55:28 - WARN thaliNotificationClient: 'peer is not available'
2017-07-18 09:55:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 823 peerDictionary should become empty
,# teardown
,2017-07-18 09:55:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-18 09:55:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 824 failed with expected error
,ok 825 peer state should be RESOLVED
,# teardown
,2017-07-18 09:55:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-18 09:55:29 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 826 First action failed
,ok 827 second action killed
# teardown
,2017-07-18 09:55:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 828 secrets are equal
ok 829 Public key matches with the server key
,ok 830 hostAddress must match
,ok 831 portNumber must match
ok 832 suggestedTCPTimeout must match
,ok 833 connectionType must match
,# teardown
,2017-07-18 09:55:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 834 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 835 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 836 All entries should be expired after 1 second
# teardown
,2017-07-18 09:55:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 837 All keys need to be available in the cache
,ok 838 All entries should be expired after 1 second
,# teardown
,2017-07-18 09:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 839 Size of the cache should be 2
ok 840 Cache doesn't contain dictionary1
,ok 841 Size of the cache should be 1
ok 842 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-18 09:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 843 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 844 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-18 09:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 845 StartUpdateAdvertisingAndListening should not be called
,ok 846 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 847 no error
ok 848 should be 204
# teardown
,2017-07-18 09:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 849 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-18 09:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 850 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-18 09:55:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 851 no error
,ok 852 should be 200
,ok 853 should be equal
,ok 854 should be equal
,ok 855 (unnamed assert)
,ok 856 no error
,ok 857 should be 204
,# teardown
,2017-07-18 09:55:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 858 error should be null
,ok 859 should be 204
,# teardown
,2017-07-18 09:55:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 860 should be 404
# teardown
,2017-07-18 09:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 861 equal keys
ok 862 not equal connection type
ok 863 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-18 09:55:41 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 864 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 865 second cleared dictionary
,2017-07-18 09:55:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 866 First start and on called correctly
,ok 867 First stop and removeListener called correctly
ok 868 first action kill called
ok 869 second action kill called
ok 870 first cleared dictionary
,ok 871 first cleared pool
ok 872 second cleared dictionary
,ok 873 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 874 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-18 09:55:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 875 listener has been set
,ok 876 peer dictionary has expected number of entries
,ok 877 Dictionary and pool have same action
,ok 878 ads match
,ok 879 PouchDB matches
,ok 880 DB Names match
,ok 881 public keys match
,ok 882 peer dictionary has expected number of entries
,ok 883 Dictionary and pool have same action
,ok 884 ads match
,ok 885 PouchDB matches
,ok 886 DB Names match
,ok 887 public keys match
,2017-07-18 09:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 888 start called once
,ok 889 One entry left
,ok 890 Dictionary and pool have same action
,ok 891 Start never called
,ok 892 Kill called once
,ok 893 no entries left
,ok 894 Third action is dead
,ok 895 peer dictionary has expected number of entries
,ok 896 Dictionary and pool have same action
,ok 897 ads match
,ok 898 PouchDB matches
,ok 899 DB Names match
,ok 900 public keys match
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
,ok 901 right error
,# teardown
,2017-07-18 09:55:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-18 09:55:44 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-18 09:55:44 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 902 right error
,# teardown
,2017-07-18 09:55:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 903 Got error as expected
,# teardown
,2017-07-18 09:55:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-18 09:55:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 904 Got error as expected
,# teardown
,2017-07-18 09:55:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-18 09:55:46 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-18 09:55:46 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 905 Got error as expected
,# teardown
,2017-07-18 09:55:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-18 09:55:48 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:55:48 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:55:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 906 should be equal
ok 907 All tests passed!
,# teardown
,2017-07-18 09:55:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-18 09:55:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:55:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:55:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 908 should be equal
ok 909 All tests passed!
,# teardown
,2017-07-18 09:55:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-18 09:55:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-18 09:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-18 09:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 910 action should be killed
,ok 911 Error should be timed out
,ok 912 No doc found
,# teardown
,2017-07-18 09:56:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-18 09:56:02 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-18 09:56:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 913 should be equal
,2017-07-18 09:56:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-18 09:56:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 914 action should be killed
,ok 915 Error should be timed out
,# teardown
,2017-07-18 09:56:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 916 socket hung up
,# teardown
,2017-07-18 09:56:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 917 same getPeerAdvertisesDataForUs
,ok 918 Same pouchdB
,ok 919 same localDbName
,ok 920 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-18 09:56:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'listening 53019'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0C13EC7D-58C9-4EE8-AE56-E60174103537
,[ThaliCore] Browser.startListening
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
,2017-07-18 09:56:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}]'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 6)'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Advertiser: session connected Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CF7E90F-A14F-40A1-994C-F57FF2477BE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
2017-07-18 09:56:09 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","generation":0}]'
2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","generation":0}'
,2017-07-18 09:56:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-18 09:56:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53022
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":53022}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 7)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":53022}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 8)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":53022}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 9)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":53022}'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 10)'
,2017-07-18 09:56:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [2, 4, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 4, 23, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 4, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 4, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 4, 23, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,8 [2, 4, 23, 24, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [2, 4, 23, 24, 25, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 4, 23, 24, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [2, 4, 23, 24, 25, 26, 27, 29, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [2, 4, 24, 25, 26, 27, 29, 30]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 4, 25, 26, 27, 29, 30]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [2, 4, 25, 27, 29, 30]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [2, 4, 25, 27, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRe,lay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [2, 4, 25, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 4, 25, 30, 31]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [2, 4, 25, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 4, 25, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Advertiser: session connected Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7 state: notConnected -> connecting
,2017-07-18 09:56:13 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [2, 4, 25, 31, 32, 33]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 4, 25, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [2, 4, 25, 31, 32, 33, 34, 35]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 4, 25, 31, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 4, 25, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 4, 25, 31, 32, 33, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
,[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:37 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:14 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed,, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53045
2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":5304,5}'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 11)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":53045}'
2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 12)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) found active relay
2017-07-18, 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":53045}'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 96EDEA21-4608-4173-8B8B-32BA5F4A9A9C (syncValue: 13)'
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96EDEA21-4608-4173-8B8B-32BA5F4A9A9C", generation: 0) found active relay
,2017-07-18 09:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":53045}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 43, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 43, 44, 45, 46]
[ThaliCore] BrowserRelay,.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 43, 44, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 44, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 46]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913F,BEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 46, 47, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,0 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 46, 47, 48, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:46
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 47, 48, 49, 50]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 47, 48, 49, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 48, 49, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 49, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 49, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:49 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 51]
[ThaliCore] TCPClient.s,ocketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,2 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 51, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [2, 4, 25, 31, 32, 33, 34, 35, 36, 38, 40, 51, 52, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [2, 4, 25, 31, 33, 34, 35, 36, 38, 40, 51, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClie,nt.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [2, 4, 25, 31, 33, 35, 36, 38, 40, 51, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.s,ocketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:16 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
,[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [2, 4, 25, 31, 33, 35, 36, 40, 51, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:36 [2, 4, 25, 31, 33, 35, 40, 51, 52, 53]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [2, 4, 25, 33, 35, 40, 51, 52, 53]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [2, 4, 25, 35, 40, 51, 52, 53]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [2, 4, 25, 40, 51, 52, 53]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [2, 4, 25, 51, 52, 53]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [2, 4, 25, 51, 52, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [2, 4, 25, 51, 52, 53, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [2, 4, 25, 51, 52, 53, 54, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [2, 4, 25, 51, 52, 53, 54, 55, 56, 57]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96EDEA21-4608-4173-8B8B-32BA5F4A9A9C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [2, 4, 25, 51, 52, 53, 54, 55, 56, 57, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [2, 4, 25, 52, 53, 54, 55, 56, 57, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [2, 4, 25, 52, 54, 55, 56, 57, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:55 [2, 4, 25, 52, 54, 56, 57, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [2, 4, 25, 52, 54, 56, 58]
,2017-07-18 09:56:17 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-18 09:56:17 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [2, 4, 25, 52, 54, 56]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,9 [2, 4, 25, 52, 54, 56, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
,[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [2, 4, 25, 54, 56, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:54 [2, 4, 25, 56, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtua,lSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:56 [2, 4, 25, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.,didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [2, 4, 25]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7CF7E90F-A14F-40A1-994C-F57FF2477BE4
2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
,2017-07-18 09:56:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18, 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
2017-07-18 09:56:17 - DEBUG thaliMo,bile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"96EDEA21-4608-4173-8B8B-32BA5F4A9A9C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-18 09:56:17 - WARN thaliNotificationC,lient: 'peer is not available'
2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
2017-07-18 09:56:17 - WARN thaliNotificationClient: 'peer is not available'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:56:17 ,-, DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:56:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with ta,rget ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-18 09:56:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeni,ngForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:56:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:56:17 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 921 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'listening 53063'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B04D5511-FFB0-4BD6-B61C-A5D82A8963CF
[ThaliCore] Browser.startListening
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4A711876-4C8F-4060-B5CA-D8ECB659AFA8
,2017-07-18 09:56:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0)
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}]'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","generation":0}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 14)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":53022}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 15)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":53022}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 16)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":null,"portNumber":53022}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 17)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17","error":null,"portNumber":53022}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [2, 4, 25, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [2, 4, 25, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [2, 4, 25, 60, 61, 62]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [2, 4, 25, 60, 61, 62, 63]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEn,countered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:60,
[ThaliCore] VirtualSocket.deinit vsID:60 [2, 4, 25, 61, 62, 63]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRe,lay.didSocketDisconnectHandler
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [2, 4, 25, 61, 62, 63, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler ,disconnecting:false
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [2, 4, 25, 61, 62, 63, 64, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket exited RunLoop vsID:64
,[ThaliCore] VirtualSocket.deinit vsID:64 [2, 4, 25, 61, 62, 63, 65]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.deinit vsID:65 [2, 4, 25, 61, 62, 63]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [2, 4, 25, 61, 62, 63, 66]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [2, 4, 25, 61, 62, 63]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD,12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [2, 4, 25, 61, 62, 63, 67]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:67
,[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [2, 4, 25, 61, 62, 63]
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 18)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":53022}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [2, 4, 25, 61, 62, 63, 68]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:68
[ThaliCore] VirtualSocket.closeStreams() vsID:68
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:68
[ThaliCore] VirtualSocket.deinit vsID:68 [2, 4, 25, 61, 62, 63]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 19)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"19","error":null,"portNumber":53022}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [2, 4, 25, 61, 62, 63, 69]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [2, 4, 25, 61, 62, 63, 69, 70]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [2, 4, 25, 61, 62, 63, 69, 70, 71]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:69
[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [2, 4, 25, 61, 62, 63, 69, 70, 71, 72]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:69
,[ThaliCore] VirtualSocket.deinit vsID:69 [2, 4, 25, 61, 62, 63, 70, 71, 72]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:71
[ThaliCore] VirtualSocket.closeStreams() vsID:71
[ThaliCore] Session.session(_:didReceive:wi,thName:fromPeer:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
[ThaliCore] Session.startOutputStream(with:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [2, 4, 25, 61, 62, 63, 70, 71, 72, 73]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:71
[ThaliCore] VirtualSocket.deinit vsID:71 [2, 4, 25, 61, 62, 63, 70, 72, 73]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:72
[ThaliCore] VirtualSocket.closeStreams() vsID:72
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo,={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:73
[ThaliCore] VirtualSocket.closeStreams() vsID:73
[ThaliCore] VirtualSocket exited RunLoop vsID:72
[ThaliCore] VirtualSocket.deinit vsID:72 [2, 4, 25, 61, 62, 63, 70, 7,3]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:73
[ThaliCore] VirtualSocket.deinit vsID:73 [2, 4, 25, 61, 62, 63, 70]
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Advertiser: session connected Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7003160D-A068-47B1-94BD-2C65360F68B1 state: notConnected -> connecting
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing mult,iConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 20)'
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45,D0-A270-46ABE636425B", generation: 0) found active relay
2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20","error":null,"portNumber":53022}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore,] Advertiser: session connected Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0840D,407-2324-415F-92C0-550C1DCC6ABD state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:74 [2, 4, 25, 61, 62, 63, 70, 74]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:75 [2, 4, 25, 61, 62, 63, 70, 74, 75]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:76 [2, 4, 25, 61, 62, 63, 70, 74, 75, 76]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:77 [2, 4, 25, 61, 62, 63, 70, 74, 75, 76, 77]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] Session.startOutputStream(with:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:78 [2, 4, 25, 61, 62, 63, 70, 74, 75, 76, 77, 78]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","generation":0}]'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","generation":0}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:76
[ThaliCore] VirtualSocket.closeStreams() vsID:76
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:76
,[ThaliCore] VirtualSocket.deinit vsID:76 [2, 4, 25, 61, 62, 63, 70, 74, 75, 77, 78]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:74
[ThaliCore] VirtualSocket.closeStreams() vsID:74
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSL,ocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:74
[ThaliCore] AdvertiserRelay.didSoc,ketDisconnectHandler removed virtual socket vsID:75
[ThaliCore] VirtualSocket.closeStreams() vsID:75
[ThaliCore] VirtualSocket.deinit vsID:74 [2, 4, 25, 61, 62, 63, 70, 75, 77, 78]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:fa,lse socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler discon,necting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:77
[ThaliCore] VirtualSocket.closeStreams() vsID:77
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:78
[ThaliCore] VirtualSocket.closeStreams() vsID:78
,[ThaliCore] VirtualSocket exited RunLoop vsID:75
,[ThaliCore] VirtualSocket.deinit vsID:75 [2, 4, 25, 61, 62, 63, 70, 77, 78]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:77
,[ThaliCore] VirtualSocket.deinit vsID:77 [2, 4, 25, 61, 62, 63, 70, 78]
[ThaliCore] VirtualSocket exited RunLoop vsID:78
,[ThaliCore] VirtualSocket.deinit vsID:78 [2, 4, 25, 61, 62, 63, 70]
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 21)'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
,2017-07-18 09:56:19 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","generation":0}]'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","generation":0}'
,2017-07-18 09:56:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-18 09:56:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A711876-4C8F-4060-B5CA-D8ECB659AFA8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A711876-4C8F-4060-B5CA-D8ECB659AFA8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
,[ThaliCore] Session.session(_:peer:didChange:) peer:57631C5C-1285-46AE-AC33-3020913FBEA7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53085
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"21","error":null,"portNumber":5308,5}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 22)'
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) found active relay
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"22","error":null,"portNumber":53085}'
2,017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 23)'
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) found active relay
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"23","error":null,"portNumber":53085}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D498A656-E3D2-4278-AB59-18ED013C38C7 (syncValue: 24)'
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "D498A656-E3D2-4278-AB59-18ED013C38C7", generation: 0) found active relay
2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"24","error":null,"portNumber":53085}'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 25)'
,2017-07-18 09:56:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE9265-B86D-4480-BD12-C8FCCBE5FDBA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7CF7E90F-A14F-40A1-994C-F57FF2477BE4", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:79 [2, 4, 25, 61, 62, 63, 70, 79]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,0 [2, 4, 25, 61, 62, 63, 70, 79, 80]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:81 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC,6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:82 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
,[ThaliCore] Session.session(_:peer:didChange:) peer:7003160D-A068-47B1-94BD-2C65360F68B1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:83 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,4 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83, 84]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,5 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83, 84, 85]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,6 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83, 84, 85, 86]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] Session.deinit peer:57631C5C-1285-46AE-AC33-3020913FBEA7
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTime,out:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:87 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83, 84, 85, 86, 87]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:88 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:89 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89]
[ThaliCore] ,Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:90 [2, 4, 25, 61, 62, 63, 70, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:81
[ThaliCore] VirtualSocket.closeStreams() vsID:81
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,81
[ThaliCore] VirtualSocket.deinit vsID:81 [2, 4, 25, 61, 62, 63, 70, 79, 80, 82, 83, 84, 85, 86, 87, 88, 89, 90]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] VirtualSocket,.handleEventOnInputStream endEncountered vsID:83
[ThaliCore] VirtualSocket.closeStreams() vsID:83
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserR,elay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:88
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:83
,[ThaliCore] VirtualSocket.deinit vsID:83 [2, 4, 25, 61, 62, 63, 70, 79, 80, 82, 84, 85, 86, 87, 88, 89, 90]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:88
[ThaliCore] VirtualSocket.de,init vsID:88 [2, 4, 25, 61, 62, 63, 70, 79, 80, 82, 84, 85, 86, 87, 89, 90]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:85
[ThaliCore] VirtualSocket.closeStreams() vsID:85
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:82
,[ThaliCore] VirtualSocket.closeStreams() vsID:82
,[ThaliCore] VirtualSocket exited RunLoop vsID:85
[ThaliCore] VirtualSocket.deinit vsID:85 [2, 4, 25, 61, 62, 63, 70, 79, 80, 82, 84, 86, 87, 89, 90]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:82
[ThaliCore] VirtualSocket.deinit vsID:82 [2, 4, 25, 61, 62, 63, 70, 79, 80, 84, 86, 87, 89, 90]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCP,Client.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:87
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:87
,[ThaliCore] VirtualSocket.deinit vsID:87 [2, 4, 25, 61, 62, 63, 70, 79, 80, 84, 86, 89, 90]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:86
[ThaliCore] VirtualSocket.closeStreams() vsID:86
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:86
[ThaliCore] VirtualSocket.deinit vsID:86 [2, 4, 25, 61, 62, 63, 70, 79, 80, 84, 89, 90]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.s,ocketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:80
[ThaliCore] VirtualSocket.closeStreams() vsID:80
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:80
[ThaliCore] VirtualSocket.deinit vsID:80 [2, 4, 25, 61, 62, 63, 70, 79, 84, 89, 90]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] Session.startOutputStream(with:) peer:0840D407-2324-415F-92C0-550C1DCC6ABD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,1 [2, 4, 25, 61, 62, 63, 70, 79, 84, 89, 90, 91]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:79
[ThaliCore] VirtualSocket.closeStreams() vsID:79
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:79
[ThaliCore] VirtualSocket.deinit vsID:79 [2, 4, 25, 61, 62, 63, 70, 84, 89, 90, 91]
[ThaliCore] TCPClient.socketDidDisco,nnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:84
[ThaliCore] VirtualSocket.closeStreams() vsID:84
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:84
[ThaliCore] VirtualSocket.deinit vsID:84 [2, 4, 25, 61, 62, 63, 70, 89, 90, 91]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:90
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:90
[ThaliCore] VirtualSocket.deinit vsID:90 [2, 4, 25, 61, 62, 63, 70, 89, 91]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D498A656-E3D2-4278-AB59-18ED013C38C7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:92 [2, 4, 25, 61, 62, 63, 70, 89, 91, 92]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:89
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:89
[ThaliCore] VirtualSocket.deinit vsID:89 [2, 4, 25, 61, 62, 63, 70, 91, 92]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] Session.startOutputStream(with:) peer:7003160D-A068-47B1-94BD-2C65360F68B1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,3 [2, 4, 25, 61, 62, 63, 70, 91, 92, 93]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:91
[ThaliCore] VirtualSocket.closeStreams() vsID:91
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandl,er disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:91
[ThaliCore] VirtualSocket.deinit vsID:91 [2, 4, 25, 61, 62, 63, 70, 92, 93]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-18 09:56:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-18 09:56:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 922 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:92
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:92
[ThaliCore] VirtualSocket.deinit vsID:92 [2, 4, 25, 61, 62, 63, 70, 93]
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:93
[ThaliCore] VirtualSocket.closeStreams() vsID:93
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:93
[ThaliCore] VirtualSocket.deinit vsID:93 [2, 4, 25, 61, 62, 63, 70]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53103
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"25","error":null,"portNumber":5310,3}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 26)'
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) found active relay
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"26","error":null,"portNumber":53103}'
2,017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 27)'
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) found active relay
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"27","error":null,"portNumber":53103}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9A60538-A18D-473B-B89F-8BF9C1999CE5 (syncValue: 28)'
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "E9A60538-A18D-473B-B89F-8BF9C1999CE5", generation: 0) found active relay
2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28","error":null,"portNumber":53103}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 29)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"29","error":null,"portNumber":53022}'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 30)'
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"30","error":null,"portNumber":53022}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:94 [2, 4, 25, 61, 62, 63, 70, 94]
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:,)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:95 [2, 4, 25, 61, 62, 63, 70, 94, 95]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:96 [2, 4, 25, 61, 62, 63, 70, 94, 95, 96]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:97 [2, 4, 25, 61, 62, 63, 70, 94, 95, 96, 97]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:97
[ThaliCore] VirtualSocket.closeStreams() vsID:97
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:97
,[ThaliCore] VirtualSocket.deinit vsID:97 [2, 4, 25, 61, 62, 63, 70, 94, 95, 96]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:96
,[ThaliCore] VirtualSocket.closeStreams() vsID:96
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:96
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:96 [2, 4, 25, 61, 62, 63, 70, 94, 95]
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:98 [2, 4, 25, 61, 62, 63, 70, 94, 95, 98]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:99 [2, 4, 25, 61, 62, 63, 70, 94, 95, 98, 99]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:94
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:94
[ThaliCore] VirtualSocket.deinit vsID:94 [2, 4, 25, 61, 62, 63, 70, 95, 98, 99]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:95
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:95
[ThaliCore] VirtualSocket.deinit vsID:95 [2, 4, 25, 61, 62, 63, 70, 98, 99]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:98
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:98
,[ThaliCore] VirtualSocket.deinit vsID:98 [2, 4, 25, 61, 62, 63, 70, 99]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:99
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:99
,[ThaliCore] VirtualSocket.deinit vsID:99 [2, 4, 25, 61, 62, 63, 70]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9A60538-A18D-473B-B89F-8BF9C1999CE5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:100 [2, 4, 25, 61, 62, 63, 70, 100]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5998E650-08FC-45D0-A270-46ABE636425B (syncValue: 31)'
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5998E650-08FC-45D0-A270-46ABE636425B", generation: 0) found active relay
,2017-07-18 09:56:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"31","error":null,"portNumber":53022}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5998E650-08FC-45D0-A270-46ABE636425B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:101 [2, 4, 25, 61, 62, 63, 70, 100, 101]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-18 09:56:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-18 09:56:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 923 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:100
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:100
[ThaliCore] VirtualSocket.deinit vsID:100 [2, 4, 25, 61, 62, 63, 70, 101]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:101
[ThaliCore] VirtualSocket.closeStreams() vsID:101
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:101
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:101 [2, 4, 25, 61, 62, 63, 70]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-18 09:56:27 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4A711876-4C8F-4060-B5CA-D8ECB659AFA8
2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5998E650-08FC-45D0-A270-46ABE636425B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D498A656-E3D2-4278-AB59-18ED013C38C7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E9A60538-A18D-473B-B89F-8BF9C1999CE5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-18 09:56:28 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:56:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:56:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [2, 4, 25, 61, 63, 70]
,2017-07-18 09:56:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 924 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 925 should throw
,ok 926 should throw
,ok 927 (unnamed assert)
,ok 928 (unnamed assert)
ok 929 (unnamed assert)
ok 930 (unnamed assert)
,ok 931 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 932 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 933 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 934 should be equal
,# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 935 should be equal
ok 936 should be equal
ok 937 should throw
,# teardown
,# setup
,# Test TransientState
,ok 938 should throw
ok 939 should throw
ok 940 should be equal
ok 941 should be equal
ok 942 should be equal
ok 943 should be equal
ok 944 (unnamed assert)
ok 945 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 946 verify failed
,ok 947 constructor called once
,ok 948 constructor called with right args
,ok 949 match start arg
,ok 950 start called once
,ok 951 stop called once
,ok 952 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-07-18 09:56:33 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 953 verify failed
,ok 954 constructor called once
,ok 955 constructor called with right args
,ok 956 match start arg
,ok 957 start called once
,ok 958 stop called once
,ok 959 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-07-18 09:56:34 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 960 verify failed
,ok 961 constructor called once
,ok 962 constructor called with right args
,ok 963 match start arg
,ok 964 start called once
,ok 965 stop called once
,ok 966 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-18 09:56:35 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 967 verify failed
,ok 968 constructor called once
,ok 969 constructor called with right args
,ok 970 match start arg
,ok 971 start called once
,ok 972 stop called once
,ok 973 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-18 09:56:36 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 974 verify failed
,ok 975 constructor called once
,ok 976 constructor called with right args
,ok 977 match start arg
,ok 978 start called once
,ok 979 stop called once
,ok 980 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-18 09:56:36 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 981 verify failed
ok 982 constructor called once
,ok 983 constructor called with right args
,ok 984 match start arg
,ok 985 start called once
,ok 986 stop called once
,ok 987 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 988 verify failed
,ok 989 constructor called once
,ok 990 constructor called with right args
,ok 991 match start arg
,ok 992 start called once
,ok 993 stop called once
,ok 994 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:37 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 995 verify failed
,ok 996 constructor called once
,ok 997 constructor called with right args
,ok 998 last start before stop
,ok 999 empty first start
,ok 1000 full second start
,ok 1001 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-18 09:56:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 1002 verify failed
ok 1003 constructor called once
ok 1004 constructor called with right args
ok 1005 start before stop
ok 1006 We got at least 3 calls to start
ok 1007 at least 3
ok 1008 default 1
ok 1009 1 run
ok 1010 default 2
,ok 1011 2 run
ok 1012 default 3
# teardown
,# setup
,# start and stop and start and stop
,ok 1013 start out null
,2017-07-18 09:56:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1014 back to null
,2017-07-18 09:56:39 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1015 still null
,ok 1016 verify failed
,ok 1017 constructor called once
,ok 1018 constructor called with right args
,ok 1019 first start before first stop
,ok 1020 first stop before second start
,ok 1021 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-18 09:56:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1022 verify failed
,ok 1023 constructor called once
,ok 1024 constructor called with right args
,ok 1025 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-18 09:56:40 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1026 verify failed
ok 1027 constructor called once
,ok 1028 constructor called with right args
,ok 1029 (unnamed assert)
,ok 1030 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-18 09:56:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1031 verify failed
,ok 1032 constructor called once
,ok 1033 constructor called with right args
,ok 1034 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-18 09:56:41 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 1035 verify failed
,ok 1036 constructor called once
,ok 1037 constructor called with right args
,ok 1038 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 1039 should be equal
ok 1040 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-18 09:56:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 1041 Got right error
,# teardown
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-18 09:56:42 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 1042 Got socket hang up
# teardown
,2017-07-18 09:56:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-18 09:56:43 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 1043 Got 500 as expected
# teardown
,2017-07-18 09:56:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 1044 should be equal
,ok 1045 revs are equal
,# teardown
,2017-07-18 09:56:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 1046 should be equal
ok 1047 revs are equal
,# teardown
,2017-07-18 09:56:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 1048 should be equal
,ok 1049 revs are equal
,ok 1050 should be equal
,ok 1051 revs are equal
,ok 1052 should be equal
,ok 1053 revs are equal
,# teardown
,2017-07-18 09:56:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/5,BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/5BD838B5-,7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-18 09:56:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1054 Our rev is old so we should fail
,# teardown
,2017-07-18 09:56:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1055 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/5,BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/5BD838B5-,7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-18 09:56:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-18 09:56:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1056 stop caused us to fail
,ok 1057 We specifically failed on a stop before put
,# teardown
,2017-07-18 09:56:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1058 failed due to stop
,ok 1059 failed due to stop
,# teardown
,2017-07-18 09:56:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1060 should be equal
,# teardown
,2017-07-18 09:56:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-18 09:56:57 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1061 Expected bad seq error
,# teardown
,2017-07-18 09:56:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1062 Different promises
,ok 1063 Timer was cancelled
,ok 1064 should be equal
,# teardown
,2017-07-18 09:57:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1065 One go and one blocked
,ok 1066 All blocked
,ok 1067 Still blocked
,ok 1068 should be equal
,# teardown
,2017-07-18 09:57:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1069 We waited long enough
,ok 1070 should be equal
,# teardown
,2017-07-18 09:57:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1071 Should have gotten same timer promise
ok 1072 Still same timer promise
,ok 1073 We waited long enough
,ok 1074 should be equal
,# teardown
,2017-07-18 09:57:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-18 09:57:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-18 09:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1075 expressPouchDB was called once
ok 1076 expressPouchDB was called with 2 arguments
,ok 1077 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 1078 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1079 PouchDB was called once
,ok 1080 PouchDB was called with 1 arguments
,ok 1081 PouchDB was called with 'dbName' as 1-st argument
,ok 1082 ThaliSendNotificationBasedOnReplication was called once
,ok 1083 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1084 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1085 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1086 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1087 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1088 ThaliPullReplicationFromNotification was called once
,ok 1089 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1090 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1091 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1092 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1093 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1094 Salti was called once
,ok 1095 Salti was called with 4 arguments
,ok 1096 Salti was called with 'dbName' as 1-st argument
,ok 1097 Salti was called with 'acl' as 2-st argument
,ok 1098 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1099 Salti was called with 'options' as 4-st argument
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:09 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'listening 53181'
2017-07-18 09:57:09 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3AEAB19F-999B-4CD8-9A52-7281F2D760BA
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:09 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "13661EC9-4D26-43FF-BEEF-D0DEEA531212", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:13661EC9-4D26-43FF-BEEF-D0DEEA531212
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:57:09 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1100 ThaliMobile.start was called once
ok 1101 ThaliMobile.start was called with 3 arguments
,ok 1102 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1103 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1104 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 1105 ThaliMobile.startListeningForAdvertisements was called once
,ok 1106 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1107 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1108 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1111 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1112 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1113 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1114 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:09 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:13661EC9-4D26-43FF-BEEF-D0DEEA531212
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:57:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18, 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:57:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1115 ThaliMobile.stop was called once
ok 1116 ThaliMobile.stop was called with 0 arguments
ok 1117 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1118 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1119 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1120 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1121 expressPouchDB was called once
ok 1122 expressPouchDB was called with 2 arguments
ok 1123 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1124 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1125 PouchDB was called once
,ok 1126 PouchDB was called with 1 arguments
,ok 1127 PouchDB was called with 'dbName' as 1-st argument
,ok 1128 ThaliSendNotificationBasedOnReplication was called once
ok 1129 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1130 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1131 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1132 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1133 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1134 ThaliPullReplicationFromNotification was called once
,ok 1135 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1136 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1137 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1138 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1139 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1140 Salti was called once
,ok 1141 Salti was called with 4 arguments
,ok 1142 Salti was called with 'dbName' as 1-st argument
,ok 1143 Salti was called with 'acl' as 2-st argument
,ok 1144 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1145 Salti was called with 'options' as 4-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53183'
2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3AA48902-8306-449D-9D6F-585CAE199967
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C7B554AF-20BB-4D6A-A967-9561763858A8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C7B554AF-20BB-4D6A-A967-9561763858A8
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1146 ThaliMobile.start was called once
ok 1147 ThaliMobile.start was called with 3 arguments
,ok 1148 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1149 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1150 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1151 ThaliMobile.startListeningForAdvertisements was called once
,ok 1152 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1153 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1154 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1155 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1156 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1157 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1158 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1159 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1160 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C7B554AF-20BB-4D6A-A967-9561763858A8
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1161 ThaliMobile.stop was called once
,ok 1162 ThaliMobile.stop was called with 0 arguments
,ok 1163 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1164 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1165 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1166 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53185'
2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C7A709DA-4251-42A3-BCE4-27E2F9BC1518
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3BC2C695-B092-4C04-A41D-FA0BF1255DA8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3BC2C695-B092-4C04-A41D-FA0BF1255DA8
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3BC2C695-B092-4C04-A41D-FA0BF1255DA8
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53187'
2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57EB0FFC-1215-4CAB-A34C-5D03CF0B5746
[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "88224DC1-B3EE-4B64-B293-5E334568031B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:88224DC1-B3EE-4B64-B293-5E334568031B
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:88224DC1-B3EE-4B64-B293-5E334568031B
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-18, 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-18 09:57:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-18 09:57:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'listening 53189'
2017-07-18 09:57:10 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9072506E-5704-4CB0-909E-2795BF2F606E
,[ThaliCore] Browser.startListening
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-18 09:57:10 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9CC30632-3F14-44B3-835F-712D7C404173", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9CC30632-3F14-44B3-835F-712D7C404173
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-18 09:57:10 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1167 ThaliMobile.start was called once
,ok 1168 ThaliMobile.start was called with 3 arguments
,ok 1169 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1170 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1171 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1172 ThaliMobile.startListeningForAdvertisements was called once
,ok 1173 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1174 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1175 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1176 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1177 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1178 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1179 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1180 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1181 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-18 09:57:10 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9CC30632-3F14-44B3-835F-712D7C404173
,2017-07-18 09:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-18 09:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-18 09:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
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
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
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
,2017-07-18 09:57:11 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:279:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-,64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07-,18 09:57:11 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-18 10:00:11 - DEBUG CoordinatedClient: 'test client failed'
2017-07-18 10:00:11 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, ,event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:,27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/5BD838B5-,7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/socket.,i,o-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5BD838B5-7B6D-45A5-BFF2-64C08CEDD897/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-18 10:00:11 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
