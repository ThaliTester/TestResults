#### Test 11335185132a4422_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/9968CF08-F92C-4415-8031-5D71852912DD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9968CF08-F92C-4415-8031-5D71852912DD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54062"
,(lldb)     command script import "/tmp/9968CF08-F92C-4415-8031-5D71852912DD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-07-20 20:19:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:19:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:19:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:19:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:19:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:19:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:19:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0F305998-D3D2-4097-8F,54-DE8EE166FB5C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0F305998-D3D2-4097-8F54-DE8EE166FB5C
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:171A4DCF-A580-4D67-ABF9-C5962E88FBDC
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:325FBF22-,B349-4B87-8C8D-E7785C98FF4E
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CDA94B0B-5F15-4321-A7DB-6D017684CB9E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CDA94B0B-5F15-4321-A7DB-6D017684CB9E
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CDA94B0B-5F15-4321-A7DB-6D017684CB9E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CDA94B0B-5F15-4321-A7DB-6D017684CB9E", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-20 20:19:22 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.668912053108215
,2017-07-20 20:19:22 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-20 20:19:22 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CDA94B0B-5F15-4321-A7DB-6D017684CB9E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CDA94B0B-5F15-4321-A7DB-6D017684CB9E", generation: 0)
,2017-07-20 20:19:25 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-20 20:19:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-20 20:19:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-20 20:19:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-20 20:19:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-20 20:19:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-20 20:19:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-20 20:19:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-20 20:19:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-20 20:19:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-20 20:19:30 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-20 20:19:30 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-20 20:19:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-20 20:19:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-20 20:19:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
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
,ok 5 should be equal
ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
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
,2017-07-20 20:20:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-20 20:20:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:39AD983B-D0AE-40E3-815A-2A3C69C9154A
[ThaliCore] Browser.startListening
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {",discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8310382A-FAEF-41D1-96DF-A1643DD76F52
[ThaliCore] Browser.startListening
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Received state ({"discoveryA,ctive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:21 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A86959DB-6686-4897-ABC0-B58E9D81F6B6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A86959DB-6686-4897-ABC0-B58E9D81F6B6
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:20:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A86959DB-6686-4897-ABC0-B58E9D81F6B6
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2259A874-512C-462A-8069-0A371767FA43", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2259A874-512C-462A-8069-0A371767FA43
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2259A874-512C-462A-8069-0A371767FA43", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:2259A874-512C-462A-8069-0A371767FA43
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2259A874-512C-462A-8069-0A371767FA43
[ThaliCore] Advertiser.stopAdvertising() peerID:2259A874-512C-462A-8069-0A371767FA43,
2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:20:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:20:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CAB1F9B1-62A3-4E4D-A23B-B0D4250937AD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CAB1F9B1-62A3-4E4D-A23B-B0D4250937AD
2017-07-20 2,0:20:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BC69B878-AE48-4154-AFBC-F7F1A8E61C82
,[ThaliCore] Browser.startListening
2017-07-20 20:20:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:20:42 - INFO thaliMobile: 'Received state ({"discoveryActive,":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:42 - INFO thaliMobile: 'F,iltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A3ADBD-7079-407F-91ED-5D6A5267C170:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A3ADBD-7079-407F-91ED-5D6A5267C170", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAB1F9B1-62A3-4E4D-A23B-B0D4250937AD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAB1F9B1-62A3-4E4D-A23B-B0D4250937AD", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:43 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:43 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CAB1F9B1-62A3-4E4D-A23B-B0D4250937AD
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWra,pper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:20:43 - DEBUG thaliMobileNati,veWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4D80EF86-38E0-401A-9B97-EDC2B291AD62
2017-07-20 2,0:21:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15044969-405F-4BFF-9487-76FE3F8D6D1E
[ThaliCore] Browser.startListening
,2017-07-20 20:21:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:21:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 20:21:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:24A3D43A-51C0-4064-AE1A-DA963F592D28
[ThaliCore] Advertiser: session connected Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:24A3D43A-51C0-4064-AE1A-DA963F592D28 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF
[ThaliCore] Advertiser: session connected Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
2017-07-20 20:21:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"551CCA29-3144-4F99-8F62-23A17B5EDC77","generation":0}'
2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 551CCA29-3144-4F99-8F62-23A17B5EDC77, (syncValue: Lf4lB6FNWXDBF7rLUBmEEMAJCIqcblu7)'
2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5,EDC77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E842B187-8856-4931-8138-58CD7DE0DE5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E842B187-8856-4931-8138-58CD7DE0DE5C", generation: 0)
,2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E842B187-8856-4931-8138-58CD7DE0DE5C","generation":0}'
2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF
,[ThaliCore] Session.session(_:peer:didChange:) peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55373
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Lf4lB6FNWXDBF7rLUBmEEMAJCIqcblu7","error":null,"portNumber":55373}'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Lf4lB6FNWXDBF7rLUBmEEMAJCIqcblu7', error: 'null', listeningPort: '55373''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:24A3D43A-51C0-4064-AE1A-DA963F592D28
2017-07-20 20:21:06 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:24A3D43A-51C0-4064-AE1A-DA963F592D28 state: connecting -> connected
,# teardown
,2017-07-20 20:21:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:21:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4D80EF86-38E0-401A-9B97-E,DC2B291AD62
2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:551CCA29-3144-4F99-8F62-23A17B5EDC77
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:24A3D43A-51C0-4064-AE1A-DA963F592D28 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", g,eneration: 0)
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55373
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Lf4lB6FNWXDBF7rLUBmEEMAJCIqcblu7","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"551CCA29-3144-4F99-8F62-23A17B5EDC77","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"551CCA29-3144-4F99-8F62-23A17B5EDC77","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:56B307C2-08AF-4A29-8560-B6A8AFB389FF
2017-07-20 2,0:21:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949
[Thal,iCore] Browser.startListening
,2017-07-20 20:21:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:21:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF
[ThaliCore] Session.deinit peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
2017-07-20 20:21:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"551CCA29-3144-4F99-8F62-23A17B5EDC77","generation":0}'
2017-07-20 20:21:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 551CCA29-3144-4F99-8F62-23A17B5EDC77, (syncValue: 3NcJJmubgxmaSHTZqISni08m6R8YjdcP)'
2017-07-20 20:21:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5,EDC77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:E842B187-8856-4931-8138-58CD7DE0DE5C:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E842B187-8856-4931-8138-58CD7DE0DE5C",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:21:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"E842B187-8856-4931-8138-58CD7DE0DE5C","generation":0}'
,2017-07-20 20:21:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
2017-07-20 20:21:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","generation":0}'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
2017-07-20 20:21:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","generation":0}'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E842B187-8856-4931-8138-58CD7DE0DE5C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E842B187-8856-4931-8138-58CD7DE0DE5C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:55,1CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,51CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:55,1CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,51CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:55,1CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,51CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0
[ThaliCore] Advertiser: session connected Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:551CCA29-3144-4F99-8F62-23A17B5EDC77 error: max retries exceeded
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3NcJJmubgxmaSHTZqISni08m6R8YjdcP","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3NcJJmubgxmaSHTZqISni08m6R8YjdcP', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerIdentifier":"551CCA29-3144-4F99-8F62-23A17B5EDC77","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"551CCA29-3144-4F99-8F62-23A17B5EDC77","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:18 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD (syncValue: sGdZ2r2b91FwSSxdrb3CQCtZpz189JZa)'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64B848E4-E7C9,-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55380
2017-07-20 20:21:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sGdZ2r2b91FwSSxdrb3CQCtZpz189JZa","error":null,"portN,umber":55380}'
2017-07-20 20:21:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sGdZ2r2b91FwSSxdrb3CQCtZpz189JZa', error: 'null', listeningPort: '55380''
,Connecting to the localhost:55380
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
Connected to the localhost:55380
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0
[ThaliCore] Session.startOutputStream(with:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-20 20:21:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:56B307C2-08AF-4A29-8560-B6A8AFB389FF
2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20,:,21:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.deinit peer:FFDDBCF9-F546-460C-848D-F0AFC9A58FC0
,[ThaliCore] BrowserManager.disconnect peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55380
[ThaliCore] Session.disconnect() p,eer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:17C71F8D-4817-4678-B647-BED88DB07F70
2017-07-20 2,0:21:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[Thali,Core] Browser.startListening
2017-07-20 20:21:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:21:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:21:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
2017-07-20 20:21:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3A9FFA67-FA8F-41C8-9E42-58712C34BE48 (syncValue: zyXy4HIf3s1Ek9QPqSaHDm5d79bgfHpm)'
,2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","generation":0}'
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
,2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E56D8C9C-324B-480C-8DDC-9842424945C0","generation":0}'
,2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3A,9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
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
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zyXy4HIf3s1Ek9QPqSaHDm5d79bgfHpm","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zyXy4HIf3s1Ek9QPqSaHDm5d79bgfHpm', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E56D8C9C-324B-480C-8DDC-9842424945C0 (syncValue: c1mMlhkfhFCbL1fqnd2aXknNK9SBYurl)'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:062AEDC2-8073-412A-9807-7AE05470E560
[ThaliCore] Advertiser: session connected Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:062AEDC2-8073-412A-9807-7AE05470E560 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:062AEDC2-8073-412A-9807-7AE05470E560
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55397
,2017-07-20 20:21:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c1mMlhkfhFCbL1fqnd2aXknNK9SBYurl","error":null,"portNumber":55397}'
,2017-07-20 20:21:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'c1mMlhkfhFCbL1fqnd2aXknNK9SBYurl', error: 'null', listeningPort: '55397''
,Connecting to the localhost:55397
,Connecting to the localhost:55397
Connecting to the localhost:55397
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] Session.startOutputStream(with:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
Connected to the localhost:55397
,Connected to the localhost:55397
,Connected to the localhost:55397
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:062AEDC2-8073-412A-9807-7AE05470E560 state: connecting -> connected
,ok 91 correct string length
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:062AEDC2-8073-412A-9807-7AE05470E560
[ThaliCore] Session.startOutputStream(with:) peer:062AEDC2-8073-412A-9807-7AE05470E560
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 4, 5, 6]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:062AEDC2-8073-412A-9807-7AE05470E560
[ThaliCore] Session.startOutputStream(with:) peer:062AEDC2-8073-412A-9807-7AE05470E560
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:062AEDC2-8073-412A-9807-7AE05470E560
[ThaliCore] Session.startOutputStream(with:) peer:062AEDC2-8073-412A-9807-7AE05470E560
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 3, 4, 5, 6, 7, 8]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 92 correct string length
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 4, 6, 7, 8]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 6, 7, 8]
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received all data: Tr1u234pAIGikjJnODTSbIKLgKM20QqZrfst4CaNzYt8vUCcl078dSPMTYRa7P1BaOMnJ3LSnibmh7vKHISt9FHxXbEz2Uo9QgNmwBOyhuHo8dLfKRJIJPlXRPAuJO5s5dxFVKB3viMpiBUpQDDTdjpFg2FRg0oeA5odsjx01aKQygtS7J,rOJtwnoh2AFvweZiMB5qYoMSleufeSIFfikWOIKRfSfix7565mEkfQ3p7KShFl9M52JNWo1AKcQWi1jqOwnOmwJZprCbPCSvvF2yTFkHKVYgbzDPHgn0uWTMoGasNxAXusGjPlcFCC33F57tXuEki1Y2p5PGbDstFnb71l78RjCC41ussjug66kAxTBGQFIR8uHSzdn1Eu50Hcse8zcmKbmfh82dAgagTUe8NDDIwHM9PYuy2ZvPVfNfChnfSMPx,AXOALbqbnKqqKV3FZixEIAOtMtpRqqGF5BHNq46cfTYx3AdF2XdR0AEwHYzJy6dly8ck6o8lDACI2DlkzU0rTIwtQz19Tm5IKLQfnwZB5sQAQtHNIWn4MeasslcHhVZ1Uszale2RPMlv8zgT3Ha1i7x3KTetIsANtBKxUOoGpbGXm3Wu3j0TdXTjGOl7BBDmRTLcUf6Mp5kujVfOZfYMsDfT2Oh2vUE67bsBGaLp2dPQUr3TRtkQKjiAgvOL7HMy,uqZn3InZNXKjxPSB3SusxlEq7GTpDImQWpYgzTQ9eVmFDU2pujLvfz63arBe4C1JMBdeVC2rdHZ8V71voopPbJoDMW9VHawcdveJTCPR83suHFGaQU09pkBK9Dt24kdv2YALBB6tvAD8KwA0OHz4Hj5vPmV12tDv6mlGmOlF1YuPWWBB74x4pPAlulCBK9yJNgOHTgp6IJp4kgmH323DMMJBD3a5fSdr91Hkhf7md5ZBDb5uCUAIbeK2uaGPYch,3,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'
2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received all data: 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[T,haliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,XbgPBeRozdahI2VZRdV1L1Ji1kjzuuyZSivJ6EKvJKRmQmuRiINNYK3s9jljc7BrWcIYy4le6EqpHibdNfQmEUibBfsznWotJDkGI21atiBaiMk6HBRI97hG73Fod9gZCKX7mYjVku39SSDok6Pt8mxHTbXlvIqza4qSaDefOvR8jPz24URP8VCKgABaBOmIJcti8f6PmfkANsrYBp62pwEEYBUY1aEeQtQoCGObarHMr8nNClV2USJAfWvSo2wQ,3zaWyqw6ZJ3PxB55kytyYxKROOx1GOvmQV0zrtyw3WQ3V4i2jg4mqksC3Dm4qi85NkHDYnnyjaWj3uHSUFyqInELlfneVV7ikyLXL2c4xzFX3tp1BHNRMoFma8UXGBPIdCsh0f8bAs3KUo0vj6hTNL03Bsg8VYAgLcEHZDniz8uGlbXA5XoMRuEsuD9KvYPrhWQIKR23jq27JspGqPymgSu6uyhBqSKMD7hgrP2KTvZSjXh9o2MyKbCZf8zWlPtz,qxYxxN0UQvqXSJPb7E2j5uTLzWUBM3amGGoo0StHLYeNcLGJ7xei2IDlZ3x4pyWQrToj2nQ4GnuKYDlLo9HvNcku7s88TQwj8kKF1kXTLnYyEGe2ItZeVE2Wxmjo6eG3dURUyZrKrC0Zq46Ttga7wrUBdc5dt7j5xRf5xIfl9qQhJV9LaoQy80bKFRPvZRDjd05PoJq2WPqm0CWxpPJ4FmFVY1FGqYNj0TWKWJD4UaQLoEbLvIsASfNwhFSLidCD,fXLln31OB94Md1X8T4AoD5dHxGP6e4c31WOLEucNP3uWIbweRltwuhDikco0Nq1SsU8qHtWDmuXX8oKCPpArqN5HICCKQoq1NA2Gjumay1RNtmM82HRGxCXQcZz3vOLgwQCgGCay5qZGepHcfhROhjsphduT2ZkHlAXr0sBH2EdZZ3tK6utWiTVWLcgrcV7TwMDt8uA21rrBYfiJAzTsMvkhyh68AEMqCGsMQfwTsOMQlRvloMqiQisj87MYrQ3p,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
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'
2017-07-20 20:21:38 ,- DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received all data: 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[,ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 6, 8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnectin,g:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
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,wn'
2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 96 got the same data back
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 20:21:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:21:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:17C71F8D-4817-4678-B647-B,ED88DB07F70
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:E56D8C9C-324B-480C-8DDC-9842424945C0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55397
[ThaliCore] Session.disconnect() peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:062AEDC2-8073-412A-9807-7AE05470E560 state: connected -> notConnected
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:062AEDC2-8073-412A-9807-7AE05470E560
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:062AEDC2-8073-412A-9807-7AE05470E560
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1
,2017-07-20 20:21:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454
[ThaliCore] Browser.startListening
,2017-07-20 20:21:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:21:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:21:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
2017-07-20 20:21:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9571CE61-1016-4A87-8C94-F0E5DAB9C517","generation":0}'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9571CE61-1016-4A87-8C94-F0E5DAB9C517, (syncValue: S20fxTDG6G3CIrRVjW0T3ZNxtTv26Eim)'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB,9C517", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
2017-07-20 20:21:44, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E56D8C9C-324B-480C-8DDC-9842424945C0","generation":0}'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C94593B-EFAB-4A2A-BBD8-57221E91DD91","generation":0}'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"749D76DB-9759-4DF1-9711-8D08EA81A735","generation":0}'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
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
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"S20fxTDG6G3CIrRVjW0T3ZNxtTv26Eim","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'S20fxTDG6G3CIrRVjW0T3ZNxtTv26Eim', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"9571CE61-1016-4A87-8C94-F0E5DAB9C517","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9571CE61-1016-4A87-8C94-F0E5DAB9C517","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4C94593B-EFAB-4A2A-BBD8-57221E91DD91 (syncValue: sj0B4W23TRGhTpzjwY1N6qCYLuFITqUC)'
,2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB
[ThaliCore] Advertiser: session connected Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55418
,2017-07-20 20:21:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sj0B4W23TRGhTpzjwY1N6qCYLuFITqUC","error":null,"portNumber":55418}'
,2017-07-20 20:21:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sj0B4W23TRGhTpzjwY1N6qCYLuFITqUC', error: 'null', listeningPort: '55418''
,Connecting to the localhost:55418
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 6, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB
,[ThaliCore] Session.startOutputStream(with:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 6, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Connected to the localhost:55418
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,Server received psk id: psk-id
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,# teardown
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 3, 6, 9]
,2017-07-20 20:21:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:21:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8976FF76-77A8-4837-BB2A-D,E6ED7BDD9E1
2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55418
[ThaliCore] Session.disconnect() p,eer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB
[ThaliCore] Advert,iserRelay.deinit
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:988FB937-F1B1-480E-BDE3-7861620E8B1B
,2017-07-20 20:22:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD
[ThaliCore] Browser.startListening
,2017-07-20 20:22:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:22:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:22:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
2017-07-20 20:22:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"749D76DB-9759-4DF1-9711-8D08EA81A735","generation":0}'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 749D76DB-9759-4DF1-9711-8D08EA81A735, (syncValue: Gz70okMApvZZAhKgwYgZKk8zyhmV5lZP)'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA8,1A735", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
2017-07-20 20:22:01, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","generation":0}'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:01 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:085DE6E9-1621-4798-93C4-92CEA205E383:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"085DE6E9-1621-4798-93C4-92CEA205E383","generation":0}'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:74,9D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,49D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:22:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Gz70okMApvZZAhKgwYgZKk8zyhmV5lZP","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:22:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Gz70okMApvZZAhKgwYgZKk8zyhmV5lZP', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:22:04 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"749D76DB-9759-4DF1-9711-8D08EA81A735","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 20:22:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"749D76DB-9759-4DF1-9711-8D08EA81A735","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 20:22:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 20:22:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0A4B69D-C26E-481F-B495-6814F733A0E6 (syncValue: IsAeQ2OgfqXQHhNhV2SPSO8,PG81YDVpp)'
2017-07-20 20:22:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F,733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:22:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55428
,2017-07-20 20:22:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IsAeQ2OgfqXQHhNhV2SPSO8PG81YDVpp","error":null,"portNumber":55428}'
,2017-07-20 20:22:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IsAeQ2OgfqXQHhNhV2SPSO8PG81YDVpp', error: 'null', listeningPort: '55428''
,Connecting to the localhost:55428
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,Connected to the localhost:55428
,2017-07-20 20:22:05 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-20 20:22:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 6, 9, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 6, 9]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F838878B-37A2-485E-B7FD-411FC460CF7F
[ThaliCore] Advertiser: session connected Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F838878B-37A2-485E-B7FD-411FC460CF7F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F838878B-37A2-485E-B7FD-411FC460CF7F
,[ThaliCore] Session.session(_:peer:didChange:) peer:F838878B-37A2-485E-B7FD-411FC460CF7F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F838878B-37A2-485E-B7FD-411FC460CF7F
[ThaliCore] Session.startOutputStream(with:) peer:F838878B-37A2-485E-B7FD-411FC460CF7F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [1, 3, 6, 9, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (18432 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (8779 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 6, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 20:22:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:988FB937-F1B1-480E-BDE3-7861620E8B1B
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20,:,22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D0A4B69D-C26E-481F-B495-6814F733A0E6
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55428
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IsAeQ2OgfqXQHhNhV2SPSO8PG81YDVpp","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F838878B-37A2-485E-B7FD-411FC460CF7F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F838878B-37A2-485E-B7FD-411FC460CF7F
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:F838878B-37A2-485E-B7FD-411FC460CF7F
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8442731C-AE7F-463B-BB82-905F5249AB00
[ThaliCore] Browser.startListening
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:22:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:,errorHandler:) Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpda,teNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:22:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"ne,t,workType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:085DE6E9-1621-4798-93C4-92CEA205E383:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"085DE6E9-1621-4798-93C4-92CEA205E383","generation":0}]'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"085DE6E9-1621-4798-93C4-92CEA205E383","generation":0}'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","generation":0}]'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","generation":0}'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B6B5F25-9D48-43DF-94FB-5D4582DB9155:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B6B5F25-9D48-43DF-94FB-5D4582DB9155", generation: 0)
2017-07-20 20:22:26 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9B6B5F25-9D48-43DF-94FB-5D4582DB9155","generation":0}]'
2017-07-20 20:22:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9B6B5F25-9D48-43DF-94FB-5D4582DB9155","generation":0}'
2017-07-20 20:22:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:22:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:22:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BB0751A3-27D6-4D76-8838-B,BBBB43AF0C5
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:30 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BE1D2DB3-32E5-446A-B4C5-EE07855BC38A
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7631C1A7-B77C-4B72-9207-49D50AAD4A49", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7631C1A7-B77C-4B72-9207-49D50AAD4A49
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7631C1A7-B77C-4B72-9207-49D50AAD4A49
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
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
,2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-20 20:22:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-20 20:22:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 20:22:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-20 20:22:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-20 20:22:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:de6a62f3-9308-425b-8a83-34df144bdb40 error: startListeningNotActive
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y9mI8qV9Wg5NmbGlnyIudtVtFw9XfzZw","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"de6a62f3-9308-425b-8a83-34df144bdb40","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"de6a62f3-9308-425b-8a83-34df144bdb40","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C6AF02B0-4F0D-4829-8F69-2833E262A474
,[ThaliCore] Browser.startListening
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
ok 132 Got null as expected
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Yuahm6Aut8mUrsOIU9QDgBFzPjxmgDfc","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-20 20:22:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7D1A7FE-EEDB-4873-8C6D-27A20C57B467
[ThaliCore] Browser.startListening
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:22:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:a711d29c-49fd-404c-a885-482982a80e86
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FEB23978-DEDA-4875-A80E-C75021896629
2017-07-20 2,0:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4CE93373-4EA4-471E-9989-210CAC263251
[Tha,l,iCore] Browser.startListening
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:22:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B6B5F25-9D48-43DF,-94FB-5D4582DB9155:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B6B5F25-9D48-43DF-94FB-5D4582DB9155", generation: 0)
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0A4B69D-C26E-481F-B495-6814F733A0E6, (syncValue: JvX1JKFvcbFkSas7Aqkg3Yln18AQlXkN)'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B6B5F25-9D48-43DF-94FB-5D4582DB9155","generation":0}'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A5BDDF1-7B91-494B-BD51-A71449C556C9","generation":0}'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCo,re] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0635C8F3-9D,F4-4970-BF0F-2DCA782B004F", generation: 0)
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0635C8F3-9DF4-4970-BF0F-2DCA782B004F","generation":0}'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9B6B5F25-9D48-43DF-94FB-5D4582DB9155:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9B6B5F25-9D48-43DF-94FB-5D4582DB9155", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:085DE6E9-1621-4798-93C4-92CEA205E383:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
2017-07-20 20:22:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"085DE6E9-1621-4798-93C4-92CEA205E383","generation":0}'
2017-07-20 20:22:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:22:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:085DE6E9-1621-4798-93C4-92CEA205E383:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F
[ThaliCore] Advertiser: session connected Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D0A4B69D,-C26E-481F-B495-6814F733A0E6 error: max retries exceeded
2017-07-20 20:22:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JvX1JKFvcbFkSas7Aqkg3Yln18AQlXkN","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:22:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JvX1JKFvcbFkSas7Aqkg3Yln18AQlXkN', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:22:49 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-20 20:22:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-20 20:22:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:22:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A5BDDF1-7B91-494B-BD51-A71449C556C9 (syncValue: eLenaYp,Rk0mNvbNhGEjEE1QuwTg5VHt7)'
2017-07-20 20:22:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A5BDDF1-7B91,-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:22:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741
[ThaliCore] Advertiser: session connected Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F
[ThaliCore] Session.startOutputStream(with:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 6, 9, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55445
,2017-07-20 20:22:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eLenaYpRk0mNvbNhGEjEE1QuwTg5VHt7","error":null,"portNumber":55445}'
,2017-07-20 20:22:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eLenaYpRk0mNvbNhGEjEE1QuwTg5VHt7', error: 'null', listeningPort: '55445''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 3, 6, 9, 13, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0) found active relay
,2017-07-20 20:22:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"z4un3PwkSsr1SBhPXj9L77hwCAHskmzX","error":null,"portNumber":55445}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0) found active relay
,2017-07-20 20:22:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y3hDSFVN5vTMx1VRHLLUMw8uQ2wWDDqg","error":null,"portNumber":55445}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741
,[ThaliCore] Session.startOutputStream(with:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 6, 9, 13, 14, 15]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,15
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 6, 9, 13, 14]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Advert,iserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Session.session(_:peer:didChange:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FEB23978-DEDA-4875,-A80E-C75021896629", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() pe,e,r:D8007DB7-899E-4F9C-BDCD-F0DF8263D741
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 6, 9, 14]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 20:22:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
[ThaliCore] Session.deinit peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741
2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNo,nTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:22:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:22:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FEB23978-DEDA-4875-A80E-C75021896629
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55445
[ThaliCore] Session.disconnect() p,eer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-20 20:22:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-20 20:22:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-20 20:22:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-20 20:22:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-20 20:22:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-20 20:22:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'listening 55449'
ok 149 Should throw
,# teardown
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'listening 55451'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 55454'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 55458'
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
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 55463'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'listening 55467'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'listening 55471'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'listening 55475'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-20 20:23:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'listening 55479'
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
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'listening 55531'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'listening 55535'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:03 - DEBUG createNativeListener: 'listening 55538'
ok 196 port must be in range
,# teardown
,2017-07-20 20:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'listening 55539'
,ok 197 second start should return same port
,# teardown
,2017-07-20 20:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'listening 55541'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
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
,listening on 55543
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:23:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3F256E69-5A96-411E-9BF5-88677F81218D
2017-07-20 2,0:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A
[ThaliCore] Browser.startListening
2017-07-20 20:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-07-20 20:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 20:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0A4B69D-C26E-481F-B495-6814F733A0E6 (syncValue: VzGVvPaOBaKSUFy7VCsZbL1MW7YeWveJ)'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retry,Count:completion:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Browser.inviteToConne,ct(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0635C8F3-9DF4-4970-BF0F-2DCA782B004F","generation":0}'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A5BDDF1-7B91-494B-BD51-A71449C556C9","generation":0}'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
2017-07-20 20:23:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","generation":0}'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","generation":0}'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:23:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VzGVvPaOBaKSUFy7VCsZbL1MW7YeWveJ","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:23:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VzGVvPaOBaKSUFy7VCsZbL1MW7YeWveJ', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:23:13 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 20:23:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 20:23:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 20:23:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-,07-20 20:23:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9B4A1C-33E8-444D-AF81-B5888BAC5468 (syncValue: JknCgeMfbZkqO0IK15BRTC3TApcZJmTI)'
2017-07-20 20:23:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliC,ore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-,33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55555
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JknCgeMfbZkqO0IK15BRTC3TApcZJmTI",,"error":null,"portNumber":55555}'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JknCgeMfbZkqO0IK15BRTC3TApcZJmTI', error: 'null', listeningPort: '55555''
,ok 210 should be equal
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB (syncValue: Hh5euNL1lV9c8TaVJTGEDedIyYnRcAvR)'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55559
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Hh5euNL1lV9c8TaVJTGEDedIyYnRcAvR","error":null,"portNumber":55559}'
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Hh5euNL1lV9c8TaVJTGEDedIyYnRcAvR', error: 'null', listeningPort: '55559''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2
[ThaliCore] Advertiser: session connected Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
[ThaliCore] Advertiser: session connected Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2
,[ThaliCore] Session.session(_:peer:didChange:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
,[ThaliCore] Session.session(_:peer:didChange:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3F256E69-5A96-411E-9BF5-88677F81218D
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55555
[ThaliCore] Session.disconnect() p,eer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55559
,[ThaliCore] Session.disconnect() peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
,[ThaliCore] Session.deinit peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:23:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 55561
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:23:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:54EFAE80-90BC-47EB-A297-F97D6E577012
2017-07-20 2,0:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84
[Thal,iCore] Browser.startListening
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
2017-07-20 20:23:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","generation":0}'
2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB, (syncValue: 6xuIqXm1O9GDuqvmduHswhzglTAgM8vk)'
2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B,0B2FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","generation":0}'
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA
[ThaliCore] Advertiser: session connected Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:AD4CB42A,-D7B2-4896-9BED-4A25A1B0B2FB error: max retries exceeded
2017-07-20 20:23:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6xuIqXm1O9GDuqvmduHswhzglTAgM8vk","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:23:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6xuIqXm1O9GDuqvmduHswhzglTAgM8vk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:23:49 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-20 20:23:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-20 20:23:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:23:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9B4A1C-33E8-444D-AF81-B5888BAC5468 (syncValue: AfbhG1D,qofwm0TxFdqQZ7g7kPYyb7EPm)'
2017-07-20 20:23:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD9B4A1C-33E8,-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AfbhG1Dqofwm0TxFdqQZ7g7kPYyb7EPm","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AfbhG1Dqofwm0TxFdqQZ7g7kPYyb7EPm', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 369058E2-8F68-45CB-BB58-78A0C9B96289 (syncValue: Mc5xNrKfJi8EyF8q0h9L9SK,BwGjuAbzm)'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2
[ThaliCore] Advertiser: session connected Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55585
,2017-07-20 20:24:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Mc5xNrKfJi8EyF8q0h9L9SKBwGjuAbzm","error":null,"portNumber":55585}'
,2017-07-20 20:24:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Mc5xNrKfJi8EyF8q0h9L9SKBwGjuAbzm', error: 'null', listeningPort: '55585''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-20 20:24:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E (syncValue: UzZNvE4goH3qBsPulPBySswLWkOKty5s)'
,2017-07-20 20:24:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:24:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55591
,2017-07-20 20:24:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UzZNvE4goH3qBsPulPBySswLWkOKty5s","error":null,"portNumber":55591}'
,2017-07-20 20:24:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UzZNvE4goH3qBsPulPBySswLWkOKty5s', error: 'null', listeningPort: '55591''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:24:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:54EFAE80-90BC-47EB-A297-F,97D6E577012
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:369058E2-8F68-45CB-BB58-78A0C9B96289
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55585
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55591
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:24:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Mc5xNrKfJi8EyF8q0h9L9SKBwGjuAbzm","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2
,[ThaliCore] Session.deinit peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'listening 55595'
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
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
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
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'listening 55596'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8F53376E-2D46-4CC8-9F84-1E08B68CE7BF
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
# teardown
2017-07-20 20:24:,07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'listening 55597'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2CDB6E33-F1F1-4877-991D-B3E6D9A0C825", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2CDB6E33-F1F1-4877-991D-B3E6D9A0C825
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2CDB6E33-F1F1-4877-991D-B3E6D9A0C825", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:2CDB6E33-F1F1-4877-991D-B3E6D9A0C825
2017-07-20 2,0:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2CDB6E33-F1F1-4877-991D-B3E6D9A0C825
[ThaliCore] Advertiser.stopAdvertising() peerID:2CDB6E33-F1F1-4877-991D-B3E6D9A0C825
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'listening 55600'
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
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-20 20:24:08 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
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
,# all services are started when we call start
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'listening 55601'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DCAC1AF3-0FB1-42BD-861F-4156ACAC7BED
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9D260635-EA23-46B7-8CC0-943FB4BB1CA9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9D260635-EA23-46B7-8CC0-943FB4BB1CA9
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:9D260635-EA23-46B7-8CC0-943FB4BB1CA9
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 20:24:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'listening 55604'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53A2760F-83AE-48C2-ADC1-8BB6CD208EDD
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D4312C52-AA0F-4242-A6AA-989020E45515", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D4312C52-AA0F-4242-A6AA-989020E45515
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,# teardown
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D4312C52-AA0F-4242-A6AA-989020E45515
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,# all services are stopped when we call stop
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'listening 55606'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:042865EC-1E09-4C12-9F06-F5E66FFDF394
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D8BB8641-91EB-4D05-9269-BA2391A70F9E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D8BB8641-91EB-4D05-9269-BA2391A70F9E
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D8BB8641-91EB-4D05-9269-BA2391A70F9E
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-20 20:24:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
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
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
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
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-20 20:24:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-20 20:24:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,# peer changes handled from a queue
,2017-07-20 20:24:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-20 20:24:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55609'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:925A52C1-A69F-42C5-97FF-9D45DC452620
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
,ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55610'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79588CBC-72E8-4010-B1DB-37B965B0C0D4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:79588CBC-72E8-4010-B1DB-37B965B0C0D4
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:79588CBC-72E8-4010-B1DB-37B965B0C0D4
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:,15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55612'
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
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55613'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F5DD9154-F64B-4E9A-8858-DCE44CC61FD6
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DE3D90D4-CB59-4229-89A7-0ABBA57B9896", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DE3D90D4-CB59-4229-89A7-0ABBA57B9896
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
2017-07-20 20:24:15 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:534D867D-8D26-4A98-8194-F5DC97795695:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "534D867D-8D26-4A98-8194-F5DC97795695", generation: 0)
2017-07-20 20:24:16 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","generation":0}]'
2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","generation":0}'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:24:16 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DE3D90D4-CB59-4229-89A7-0ABBA57B9896
2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 20:24:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-20 20:24:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'listening 55615'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:09D2BF65-9C60-4653-8990-CE41CD5662DA
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6
2017-07-20 2,0:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 369058E2-8F68-45CB-BB58-78A0C9B96289 (syncValue: HjhgYfno2grB9YbPQofzGUbKGUM6vMT1)'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
2017-07-20 20:24:19 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}]'
2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:24:19 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE86867-1917-499E-88A8-9DE0439C821C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE86867-1917-499E-88A8-9DE0439C821C", generation: 0)
2017-07-20 20:24:20 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","generation":0}]'
2017-07-20 20:24:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","generation":0}'
,2017-07-20 20:24:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:24:20 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 20:24:20 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
2017-07-20 20:24:20 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
2017-07-20 20:24:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:24:20 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
2017-07-20 20:24:21 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
2017-07-20 20:24:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:24:21 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,9058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,69058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:24:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HjhgYfno2grB9YbPQofzGUbKGUM6vMT1","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:24:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HjhgYfno2grB9YbPQofzGUbKGUM6vMT1', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:24:24 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:24:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 20:24:24 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:24:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:369058E2-8F68-45CB-BB58-78A0C9B96289
2017-07-20 20:24:24 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
,2017-07-20 20:24:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 603D95D4-183F-4EC9-B17D-817535F98047 (syncValue: 0TA7ZyGALvrfZvx4zHlv4j8weRZiBYTv)'
2017-07-20 20:24:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "603D,95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55623
2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0TA7ZyGALvrfZvx4zHlv4j8weRZiBYTv",,"error":null,"portNumber":55623}'
2017-07-20 20:24:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0TA7ZyGALvrfZvx4zHlv4j8weRZiBYTv', error: 'null', listeningPort: '55623''
,2017-07-20 20:24:27 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8163C1B7-8E0B-445A-BE76-E11988518152
[ThaliCore] Advertiser: session connected Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8163C1B7-8E0B-445A-BE76-E11988518152 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 6, 9, 14, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:28 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:28 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
ok 284 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8163C1B7-8E0B-445A-BE76-E11988518152
,[ThaliCore] Session.session(_:peer:didChange:) peer:8163C1B7-8E0B-445A-BE76-E11988518152 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8163C1B7-8E0B-445A-BE76-E11988518152
,[ThaliCore] Session.startOutputStream(with:) peer:8163C1B7-8E0B-445A-BE76-E11988518152
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 6, 9, 14, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8163C1B7-8E0B-445A-BE76-E11988518152 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8163C1B7-8E0B-445A-BE76-E11988518152
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [1, 3, 6, 9, 14, 16]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3, 6, 9, 14]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:24:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55623
[ThaliCore] Session.disconnect() peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] BrowserManager.disconnect peer:603D95D4-183F-4EC9-B17D-817535F98047
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0TA7ZyGALvrfZvx4zHlv4j8weRZiBYTv","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:8163C1B7-8E0B-445A-BE76-E11988518152
,# will fail bad PSK connection between peers
,[ThaliCore] Session.deinit peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserRelay.deinit
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
2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-20 20:24:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-20 20:24:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:24:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 20:24:32 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
,ok 293 error should be null
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
,2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'listening 55626'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'listening 55627'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42FA3737-E7DE-47B8-B6AA-7B966ACD02D5
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}]'
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}'
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:24:34 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'listening 55628'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F78E2F4A-4A85-456A-B75E-2FCB70619B8D", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:F78E2F4A-4A85-456A-B75E-2FCB70619B8D
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
ok 314 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F78E2F4A-4A85-456A-B75E-2FCB70619B8D", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:F78E2F4A-4A85-456A-B75E-2FCB70619B8D
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F78E2F4A-4A85-456A-B75E-2FCB70619B8D
,[ThaliCore] Advertiser.stopAdvertising() peerID:F78E2F4A-4A85-456A-B75E-2FCB70619B8D
2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'listening 55631'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'listening 55632'
,ok 332 first call should succeed
,ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
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
,2017-07-20 20:24:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c43e3e55-e1e9-443a-a6ec-e5bb453ac3ed","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 344 should be calle,d once
ok 345 should not have been called more than once
,# teardown
,2017-07-20 20:24:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c43e3e55-e1e9-443a-a6ec-e5bb453ac3ed","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"de4afcca-502d-4f07-8e7d-ae32674ea6a4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 354 peer should be available
,ok 355 cache contains native peer
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"de4afcca-502d-4f07-8e7d-ae32674ea6a4","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d46e7573-8958-4f62-abbc-513d89b498be","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 362 peer should be available
,ok 363 cache contains wifi peer
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d46e7573-8958-4f62-abbc-513d89b498be","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
,ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
,ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b7b19407-3b80-458a-a8c5-43701fe025ce","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2ab609e0-e96e-477b-89af-7d23b80278f5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b7b19407-3b80-458a-a8c5-43701fe025ce","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2ab609e0-e96e-477b-89af-7d23b80278f5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"becdb8fb-af80-4f90-a977-46f513b4f283","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 376 peer is available
,# teardown
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"becdb8fb-af80-4f90-a977-46f513b4f283","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c4976b60-7b8b-4727-bb55-51917adf3fb8","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c4976b60-7b8b-4727-bb55-51917adf3fb8","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c4976b60-7b8b-4727-bb55-51917adf3fb8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'listening 55633'
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9a7d60a-99f7-44fe-ba2f-56fb473320b8","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9a7d60a-99f7-44fe-ba2f-56fb473320b8","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b9a7d60a-99f7-44fe-ba2f-56fb473320b8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:39 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-20 20:24:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'listening 55634'
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dc4f42c3-66fe-4184-9832-75392220e840","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dc4f42c3-66fe-4184-9832-75392220e840","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"af70b03f-ecaa-418d-8b7f-03b9c8754d27","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 404 peer should be ,available
2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"af70b03f-ecaa-418d-8b7f-03b9c8754d27","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 405 peer, should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'listening 55635'
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ea24d48e-31c7-40d2-a6e9-04a3b704dadd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 first peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b523fe5b-ea85-4947-8980-be4dd97870b3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 411 second peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b523fe5b-ea85-4947-8980-be4dd97870b3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b523fe5b-ea85-4947-8980-be4dd97870b3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b523fe5b-ea85-4947-8980-be4dd97870b3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ea24d48e-31c7-40d2-a6e9-04a3b704dadd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'listening 55636'
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e99353c1-74f7-4fd0-9f66-f01eb33a4931","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a66000e2-bd7e-4d34-bd09-43cc8677772b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e99353c1-74f7-4fd0-9f66-f01eb33a4931","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a66000e2-bd7e-4d34-bd09-43cc8677772b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:41 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-20 20:24:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
,ok 432 error should be null
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
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7af569f5-3fa3-4420-a4ae-570706e1192d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7af569f5-3fa3-4420-a4ae-570706e1192d","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7af569f5-3fa3-4420-a4ae-570706e1192d","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7af569f5-3fa3-4420-a4ae-570706e1192d","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 440 new host handled correctly
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7af569f5-3fa3-4420-a4ae-570706e1192d","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
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
ok 450 error should be null
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
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-20 20:24:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'listening 55637'
2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3994808c-d4bf-4b88-8523-b88022cd10f2","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3994808c-d4bf-4b88-8523-b88022cd10f2","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'listening 55638'
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52e2b031-61f0-4da9-8e36-4ba42a42559d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:52e2b031-61f0-4da9-8e36-4ba42a42559d
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"52e2b031-61f0-4da9-8e36-4ba42a42559d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
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
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'listening 55639'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:95EAC9C2-F64D-49BD-A648-E3CB9D6670EB
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,2017-07-20 20:24:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"642794a5-e426-420f-86f6-50e03ddff54d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-20 20:24:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eebe43e4-d75b-4e19-a45c-df243c794ff6","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"642794a5-e426-420f-86f6-50e03ddff54d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"eebe43e4-d75b-4e19-a45c-df243c794ff6","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}]'
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}'
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'listening 55640'
2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2f0bdcc6-762f-4e86-9cfa-50217d7a25da","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fe52750c-15c6-497f-8dda-52d01abda23a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2f0bdcc6-762f-4e86-9cfa-50217d7a25da","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fe52750c-15c6-497f-8dda-52d01abda23a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-20 20:24:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
,ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'listening 55641'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:67C489F9-6AF1-4BB0-8C69-0EC08B235189
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
ok 524 error should be null
,ok 525 error should be null
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}]'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 603D95D4-183F-4EC9-B17D-817535F98047 (syncValue: 0)'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","generation":0}]'
2017-07-20 20:24:49 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","generation":0}'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","generation":0}]'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","generation":0}'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
2017-07-20 20:24:50 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}]'
2017-07-20 20:24:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}'
,2017-07-20 20:24:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:24:50 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,3D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,03D95D4-183F-4EC9-B17D-817535F98047", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:24:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,0 20:24:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:24:51 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C2BF93C0-656C-4565-8E64-9D866559AD79 (syncValue: 1)'
2017-07-20 20:24:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-20 20:24:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
[ThaliCore] Advertiser: session connected Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8B231361-A704-4021-AD20-3523B68F9F1A state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
[ThaliCore] Advertiser: session connected Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
,[ThaliCore] Session.session(_:peer:didChange:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58 state: connecting -> connected
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55647
,2017-07-20 20:24:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":55647}'
,2017-07-20 20:24:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 640FCAA2-E8A9-419B-A56C-205453BA21D8 (syncValue: 2)'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
[ThaliCore] Session.startOutputStream(with:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 3, 6, 9, 14, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-20 20:24:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64,0FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 6, 9, 14, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:56 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:56 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
[ThaliCore] Session.session(_:peer:didChange:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B231361-A704-4021-AD20-3523B68F9F1A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
[ThaliCore] Session.startOutputStream(with:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 3, 6, 9, 14, 18, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55653
,2017-07-20 20:24:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":55653}'
,[ThaliCore] BrowserManager.disconnect peer:603D95D4-183F-4EC9-B17D-817535F98047
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 6, 9, 14, 18, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:59 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:59 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,2017-07-20 20:25:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:25:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] Advertiser.stopAdvertising() peerID:67C489F9-6AF1-4BB0-8C69-0EC08B235189
[ThaliCore] VirtualSocket.closeStreams() vsID:19
2017-07-20 20:25:00 - DEBUG thaliMobileNative,Wrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:25:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
2017-07-20 20:25:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] Brow,serManager.stopListeningForAdvertisements()
[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 6, 9, 14, 18, 20, 21]
,[ThaliCore] Browser.stopListening()
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:25:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 6, 9, 14, 18, 20]
,2017-07-20 20:25:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:25:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeS,treams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 6, 9, 14, 20]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:20 [1, 3, 6, 9, 14]
,ok 527 error should be null
,ok 528 error should be null
,# setup
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-20 20:25:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
,2017-07-20 20:25:01 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-20 20:25:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
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
,ok 615 already enqueued
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
,ok 624 first kill
,ok 625 second NOOP kill
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
ok 638 Kill should have been calle,d at least once
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
,ok 642 Got Null
,ok 643 Got another null
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 649 should have gotten null
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-20 20:25:12 - DEBUG thaliPeer,PoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 650 Should have stopped nicely
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-20 20:25:12 - D,EBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 651 Still looking for null
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
,ok 655 (unnamed assert)
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
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
,ok 668 is an agent
ok 669 Second does not throw
2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
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
,ok 680 public keys match!
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
,ok 686 correct error message
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
,ok 697 must return null after successful call
,# teardown
,2017-07-20 20:25:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-20 20:25:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
,ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-20 20:25:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 709 should be equal
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
ok 742 peerDictionalty contains 2 peers
,ok 743 bluetooth peer's notification has correct connection type
ok 744 tcp peer's notification has correct connection type
,2017-07-20 20:25:37 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-20 20:25:37 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 20:25:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
2017-07-20 20:25:38 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-20 20:25:38 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 20:25:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
ok 748 entry is resolved
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
,ok 759 suggestedTCPTimeout must match
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
,ok 765 action should be resolved with NETWORK_PROBLEM error
,ok 766 correct number of requests
,ok 767 correct number of failures
,ok 768 correct final peer state
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
# teardown
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
ok 794 should be 204
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
ok 798 should be 200
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
,# teardown
,2017-07-20 20:25:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-20 20:25:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
,ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-20 20:25:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
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
,ok 821 listener has been set
,ok 822 peer dictionary has expected number of entries
,ok 823 Dictionary and pool have same action
,ok 824 ads match
,ok 825 PouchDB matches
,ok 826 DB Names match
,ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
ok 829 Dictionary and pool have same action
,ok 830 ads match
ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-07-20 20:25:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
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
,2017-07-20 20:26:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-20 20:26:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-20 20:26:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:12 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
# teardown
,2017-07-20 20:26:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-20 20:26:16 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 20:26:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-20 20:26:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-20 20:26:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:20 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-20 20:26:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-20 20:26:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
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
,ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-20 20:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'listening 55780'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Browser.startListening
2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B3A4F582-40E9-402A-9159-D09698B7BF1C
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
2017-07-20 20:26:28 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}]'
2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:26:28 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 3)'
2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6,-9EE7-B3AAB0664285", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] Session.init(session:identifier:connected,:notConnected:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}]'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Advertiser: session connected Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55783
,2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":55783}'
,2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 4)'
,2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 3, 6, 9, 14, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Advertiser: session connected Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [1, 3, 6, 9, 14]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 3, 6, 9, 14, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: notConnected -> connecting
,2017-07-20 20:26:31 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 3, 6, 9, 14, 23, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 6, 9, 14, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 6, 9, 14, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 3, 6, 9, 14, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 6, 9, 14, 23, 24, 25, 27]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 6, 9, 14, 23, 24, 25, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [1, 3, 6, 9, 14, 23, 24, 25, 27]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 6, 9, 14, 23, 24, 25, 27, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 6, 9, 14, 23, 24, 25, 27, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:29 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30]
,2017-07-20 20:26:33 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] Session.session(_:peer:didChange:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,1 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55796
,2017-07-20 20:26:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":55796}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 32, 34]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketD,idDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:26:34 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,2 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,3 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34,, 36, 37, 39, 40, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 36, 37, 39, 40, 42, 43, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:ni,l
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:25
2017-07-20 20:26:35 - DEBUG thaliRep,licationPeerAction: 'Got error on replication -  500 socket hang up -1'
2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket clos,ed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDi,sconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:30
2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] Sessio,n.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 6, 9, 14, 23, 24, 25, 27, 30, 34, 36, 37, 39, 40, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NS,LocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed,, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSo,cket.deinit vsID:24 [1, 3, 6, 9, 14, 23, 25, 27, 30, 34, 36, 37, 39, 40, 42, 43, 44, 45, 46]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote pe,er" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInf,o={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 6, 9, 14, 25, 27, 30, 34, 36, 37, 39, 40, 42, 43, 44, 45, 46]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCor,e] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[T,haliCore] VirtualSocket.deinit vsID:25 [1, 3, 6, 9, 14, 27, 30, 34, 36, 37, 39, 40, 42, 43, 44, 45, 46]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] BrowserRelay.didSocketDisconnectHand,ler socket removed, count:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:30 [1, 3, 6, 9, 14, 27, 34, 36, 37, 39, 40, 42, 43, 44, 45, 46]
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 3, 6, 9, 14, 27, 34, 37, 39, 40, 42, 43, 44, 45, 46]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSoc,ket.deinit vsID:39 [1, 3, 6, 9, 14, 27, 34, 37, 40, 42, 43, 44, 45, 46]
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 6, 9, 14, 27, 34, 37, 40, 42, 43, 45, 46]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 6, 9, 14, 27, 34, 37, 42, 43, 45, 46]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 6, 9, 14, 27, 34, 37, 42, 43, 46]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 6, 9, 14, 27, 37, 42, 43, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 6, 9, 14, 27, 37, 42, 43]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] VirtualSocket.handleEventOnInputStream endEn,countered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[T,haliCore] VirtualSocket.deinit vsID:37 [1, 3, 6, 9, 14, 27, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adve,rtiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket ,exited RunLoop vsID:43
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 6, 9, 14, 27, 42]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 6, 9, 14, 27]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B3A4F582-40E9-402A-9159-D09698B7BF1C
,2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:26:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:26:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:26:36 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-20 20:26:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-07-20 20:26:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:26:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 6, 9, 14]
,ok 867 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'listening 55812'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] Browser.startListening
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 3, 6, 9, 14, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NSLocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [1, 3, 6, 9, 14]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 3, 6, 9, 14, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [1, 3, 6, 9, 14]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}]'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}]'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 5)'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) found active relay
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":55783}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 6)'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) found active relay
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":55796}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [1, 3, 6, 9, 14, 49]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [1, 3, 6, 9, 14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 3, 6, 9, 14, 50]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [1, 3, 6, 9, 14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 3, 6, 9, 14, 51]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 3, 6, 9, 14, 51, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [1, 3, 6, 9, 14, 51]
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 7)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":55783}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 3, 6, 9, 14, 51, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:53 [1, 3, 6, 9, 14, 51]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 8)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":55796}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 3, 6, 9, 14, 51, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:54 [1, 3, 6, 9, 14, 51]
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,5 [1, 3, 6, 9, 14, 51, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:55 [1, 3, 6, 9, 14, 51]
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 9)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":55783}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [1, 3, 6, 9, 14, 51, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
,[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [1, 3, 6, 9, 14, 51]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 10)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-,A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [1, 3, 6, 9, 14, 51, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F909,16C-93B2-4AEA-A154-B951CA01BF30", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":55796}'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSock,et.deinit vsID:57 [1, 3, 6, 9, 14, 51]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 3, 6, 9, 14, 51, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:58 [1, 3, 6, 9, 14, 51]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}]'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}]'
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:26:39 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:26:39 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 086240B2-409F-45A5-A6CA-A35C459065A0 (syncValue: 11)'
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08,6240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [1, 3, 6, 9, 14, 51, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:59 [1, 3, 6, 9, 14, 51]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] Advertiser: session connected Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] Advertiser: session connected Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EB94D05F-0832-4170-8059-233820381033 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55828
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":55828}'
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5E079B7C-5E99-4561-83E0-A4660711AA6F (syncValue: 12)'
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [1, 3, 6, 9, 14, 51, 60]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.deinit peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] VirtualSocket.deinit vsID:60 [1, 3, 6, 9, 14, 51]
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [1, 3, 6, 9, 14, 51, 61]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-20 20:26:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [1, 3, 6, 9, 14, 51]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
,[ThaliCore] Session.session(_:peer:didChange:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] Session.startOutputStream(with:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [1, 3, 6, 9, 14, 51, 62]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] VirtualSocket.deinit vsID:62 [1, 3, 6, 9, 14, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
,[ThaliCore] Session.startOutputStream(with:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [1, 3, 6, 9, 14, 51, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
,[ThaliCore] VirtualSocket.deinit vsID:63 [1, 3, 6, 9, 14, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:55783
[ThaliCore] Session.disconnect() peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
2017-07-20 20:26:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:26:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:43 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-20 20:26:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}]'
2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:26:44 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 20:26:44 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:55796
[ThaliCore] Session.disconnect() peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55835
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":55835}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EB94D05F-0832-4170-8059-233820381033
,2017-07-20 20:26:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:44 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 13)'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB94D05F-0832-4170-8059-233820381033 state: connecting -> connected
,[ThaliCore] Session.deinit peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":"Peer is unavailable","portNumber":null}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 14)'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [1, 3, 6, 9, 14, 51, 64]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB94D05F-0832-4170-8059-233820381033
,[ThaliCore] Session.startOutputStream(with:) peer:EB94D05F-0832-4170-8059-233820381033
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [1, 3, 6, 9, 14, 51, 64, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
,[ThaliCore] VirtualSocket.deinit vsID:64 [1, 3, 6, 9, 14, 51, 65]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [1, 3, 6, 9, 14, 51, 65, 66]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:65
,[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket.deinit vsID:65 [1, 3, 6, 9, 14, 51, 66]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB94D05F-0832-4170-8059-233820381033
,[ThaliCore] Session.startOutputStream(with:) peer:EB94D05F-0832-4170-8059-233820381033
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [1, 3, 6, 9, 14, 51, 66, 67]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:26:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-20 20:26:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [1, 3, 6, 9, 14, 51, 67]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:67
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [1, 3, 6, 9, 14, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3F90916C,-93B2-4AEA-A154-B951CA01BF30 error: max retries exceeded
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":"Connection could not be established","portNumber":null}'
2017-07-20 20:26:55 - DEBUG thaliMob,ileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer avai,l,ability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wi,th {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4A,EA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 15)'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
,[ThaliCore] Session.deinit peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":"Peer is unavailable","portNumber":null}'
2017-07-,20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 16)'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-20 20:26:55 - DEBUG thaliPeerPoolDefault: 'Got err   Connection could not be established'
,2017-07-20 20:26:55 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}]'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":"Peer is unavailable","portNumber":null}'
2017-07-,20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:58 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC
2017-07-20 20:26:58 - DEBUG thaliMobileN,ativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] BrowserManager.disconnect peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285
2017-07-20 20:26:58 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is, unavailable'
2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 20:26:5,8 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Session.deinit peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:26:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 20:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [1, 3, 6, 9, 14]
,2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:26:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.disconnect peer:3F90916C-93B2-4AEA-A154-B951CA01BF30
,ok 870 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 871 should throw
,ok 872 should throw
,ok 873 (unnamed assert)
,ok 874 (unnamed assert)
,ok 875 (unnamed assert)
,ok 876 (unnamed assert)
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
,# teardown
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
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 960 back to null
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
ok 986 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-20 20:27:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:27:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 987 Got right error
,# teardown
,2017-07-20 20:27:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-20 20:27:16 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 988 Got socket hang up
,# teardown
,2017-07-20 20:27:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-20 20:27:17 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 989 Got 500 as expected
,# teardown
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
,2017-07-20 20:27:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/0,40B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/040B26D0-,5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-20 20:27:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
ok 1000 Our rev is old so we should fail
,# teardown
,2017-07-20 20:27:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1001 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/0,40B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/040B26D0-,5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-20 20:27:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-20 20:27:25 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1002 stop caused us to fail
,ok 1003 We specifically failed on a stop before put
,# teardown
,2017-07-20 20:27:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 1007 Expected bad seq error
,# teardown
,2017-07-20 20:27:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1008 Different promises
,ok 1009 Timer was cancelled
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
,ok 1018 Still same timer promise
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
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'listening 55920'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:988B6F12-7FAB-4F10-8681-4208243228F1
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "69B790A0-374A-412F-92F3-DCE34179EA5A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:69B790A0-374A-412F-92F3-DCE34179EA5A
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-20 20:27:41 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:69B790A0-374A-412F-92F3-DCE34179EA5A
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1061 ThaliMobile.stop was called once
,ok 1062 ThaliMobile.stop was called with 0 arguments
,ok 1063 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1065 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 55922'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:68E970FC-1CAB-4DD4-B15F-DC3952C951F3
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "193D9470-1DCF-41E2-BD51-82302EE70E10", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:193D9470-1DCF-41E2-BD51-82302EE70E10
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:193D9470-1DCF-41E2-BD51-82302EE70E10
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1107 ThaliMobile.stop was called once
,ok 1108 ThaliMobile.stop was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1111 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'listening 55924'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A6D31F68-0650-4196-BD19-C775F6F0586C
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "140B3E4D-1D10-451F-815D-2DAE37872960", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:140B3E4D-1D10-451F-815D-2DAE37872960
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:140B3E4D-1D10-451F-815D-2DAE37872960
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'listening 55926'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F1DA022A-D741-4054-BDC9-72384FCCDBFF
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "909E55DD-15AC-467A-9107-EE68FB0BC2E9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:909E55DD-15AC-467A-9107-EE68FB0BC2E9
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:909E55DD-15AC-467A-9107-EE68FB0BC2E9
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'listening 55928'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7D4BA948-C44C-412F-B6A3-2D98840804CA
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4BAD8D8E-4679-4625-ABFF-20DF3C2F479E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4BAD8D8E-4679-4625-ABFF-20DF3C2F479E
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,[ThaliCore] Advertiser.stopAdvertising() peerID:4BAD8D8E-4679-4625-ABFF-20DF3C2F479E
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
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
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
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
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
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
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:285:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-,A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07-,20 20:27:44 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-20 20:30:44 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-20 20:30:45 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-20 20:30:45 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-20 20:30:45 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/c,ontainers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/ww,w/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/040B26D0-5954-4F83-B25C-A36A882B0C6E/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
,2017-07-20 20:30:45 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
