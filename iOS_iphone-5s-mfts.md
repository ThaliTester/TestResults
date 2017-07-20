#### Test 11335185132a4422_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/71AD3FD5-B8D0-47D1-9C57-493563B6086E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/71AD3FD5-B8D0-47D1-9C57-493563B6086E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54064"
,(lldb)     command script import "/tmp/71AD3FD5-B8D0-47D1-9C57-493563B6086E/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
,2017-07-20 20:19:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:19:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:19:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:19:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:19:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:19:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:19:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98D320E7-22D1-4790-89,82-487992E595B5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:98D320E7-22D1-4790-8982-487992E595B5
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C731CFE-7F92-4490-A3D5-137BECF14156
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C8FF2941-,7C2B-44C7-B9A2-1FDD3979A7F4
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF4DCF29-9C09-400A-9BC6-48D4BFAB1DC6", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:BF4DCF29-9C09-400A-9BC6-48D4BFAB1DC6
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4DCF29-9C09-400A-9BC6-48D4BFAB1DC6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4DCF29-9C09-400A-9BC6-48D4BFAB1DC6", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-20 20:19:30 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.512791156768799
,2017-07-20 20:19:30 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-20 20:19:30 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF4DCF29-9C09-400A-9BC6-48D4BFAB1DC6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF4DCF29-9C09-400A-9BC6-48D4BFAB1DC6", generation: 0)
,2017-07-20 20:19:33 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-20 20:19:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-20 20:19:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-20 20:19:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-20 20:19:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-20 20:19:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-20 20:19:37 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-20 20:19:37 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-20 20:19:37 - DEBUG CoordinatedClient: 'connected to the test server'
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
,2017-07-20 20:19:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-20 20:19:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
,ok 30 testing promises
,# teardown
,# setup
,# mix enqueue and enqueueAtTop
,ok 31 fourth
,ok 32 fourth
,ok 33 second
,ok 34 secondPromise - in then
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
,2017-07-20 20:20:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-20 20:20:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-20 20:20:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 61 correctly stringifies peer
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:37A56B7A-AF6B-4EDC-8941-B9668314911C
[ThaliCore] Browser.startListening
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DE099DF3-756B-4829-A4D3-B90776CBC8CE
[ThaliCore] Browser.startListening
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6334EABA-3BAE-4F83-9395-5AF266E892AB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6334EABA-3BAE-4F83-9395-5AF266E892AB
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6334EABA-3BAE-4F83-9395-5AF266E892AB
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A49B394-172E-41D9-99C1-AF6D20938396", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1A49B394-172E-41D9-99C1-AF6D20938396
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A49B394-172E-41D9-99C1-AF6D20938396", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:1A49B394-172E-41D9-99C1-AF6D20938396
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1A49B394-172E-41D9-99C1-AF6D20938396
[ThaliCore] Advertiser.stopAdvertising() peerID:1A49B394-172E-41D9-99C1-AF6D20938396,
2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e).'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:20:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "25922B3E-9C4F-42FE-A1D6-0315DF85D772", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:25922B3E-9C4F-42FE-A1D6-0315DF85D772
2017-07-20 2,0:20:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4E1679E1-6D0E-4B56-A8FF-217F1A270812
[ThaliCore] Browser.startListen,ing
2017-07-20 20:20:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:20:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true,}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] Browser.stopListening()
2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:20:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:20:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:25922B3E-9C4F-42FE-A1D6-0,315DF85D772
2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:551CCA29-3144-4F99-8F62-23A17B5EDC77
2017-07-20 2,0:21:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:24A3D43A-51C0-4064-AE1A-DA963F592D28
[Thal,i,Core] Browser.startListening
,2017-07-20 20:21:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:21:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 20:21:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
2017-07-20 20:21:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","generation":0}'
2017-07-20 20:21:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D80EF86-38E0-401A-9B97-EDC2B291AD62, (syncValue: I0wm16vMcCZn8LNBPN3oNpYzdZdV2M1P)'
,2017-07-20 20:21:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:15044969-405F-4BFF-9487-76FE3F8D6D1E
[ThaliCore] Advertiser: session connected Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:15044969-405F-4BFF-9487-76FE3F8D6D1E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E842B187-8856-4931-8138-58CD7DE0DE5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E842B187-8856-4931-8138-58CD7DE0DE5C", generation: 0)
,2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E842B187-8856-4931-8138-58CD7DE0DE5C","generation":0}'
,2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:15044969-405F-4BFF-9487-76FE3F8D6D1E
,[ThaliCore] Session.session(_:peer:didChange:) peer:15044969-405F-4BFF-9487-76FE3F8D6D1E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55502
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"I0wm16vMcCZn8LNBPN3oNpYzdZdV2M1P","error":null,"portNumber":55502}'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'I0wm16vMcCZn8LNBPN3oNpYzdZdV2M1P', error: 'null', listeningPort: '55502''
,2017-07-20 20:21:06 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-20 20:21:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:21:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:551CCA29-3144-4F99-8F62-23A17B5EDC77
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55502
,[ThaliCore] Session.disconnect() peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[ThaliCore] Session.session(_:peer:didChange:) peer:15044969-405F-4BFF-9487-76FE3F8D6D1E state: connected -> notConnected
[ThaliCore] Advertiser: session n,otConnected Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSessi,on()
[ThaliCore] Session.disconnect() peer:15044969-405F-4BFF-9487-76FE3F8D6D1E
[ThaliCore] AdvertiserRelay.deinit
2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-20 20:21:06 - D,EBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3A9FFA67-FA8F-41C8-9E42-58712C34BE48
2017-07-20 2,0:21:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42690737-DEF7-4FCF-A261-1577781FF856
[ThaliCore] Browser.startListening
2017-07-20 20:21:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:21:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:15044969-405F-4BFF-9487-76FE3F8D6D1E
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
2017-07-20 20:21:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","generation":0}'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D80EF86-38E0-401A-9B97-EDC2B291AD62, (syncValue: rM3RLAaMxjIhbSmyp5XEulJ3WVotrUIr)'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B29,1AD62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
,2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","generation":0}'
,2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"56B307C2-08AF-4A29-8560-B6A8AFB389FF","generation":0}'
,2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
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
2017-07-20 20:21:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rM3RLAaMxjIhbSmyp5XEulJ3WVotrUIr","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rM3RLAaMxjIhbSmyp5XEulJ3WVotrUIr', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:19 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:21:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:21:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD (syncValue: sBNOCkb,XCebBBqCjmasHvifujgQgWVaq)'
2017-07-20 20:21:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64B848E4-E7C9,-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55507
2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sBNOCkbXCebBBqCjmasHvifujgQgWVaq",,"error":null,"portNumber":55507}'
2017-07-20 20:21:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sBNOCkbXCebBBqCjmasHvifujgQgWVaq', error: 'null', listeningPort: '55507''
,Connecting to the localhost:55507
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
,Connected to the localhost:55507
,2017-07-20 20:21:22 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 20:21:22 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-07-20 20:21:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:3A9FFA67-FA8F-41C8-9E42-58712C34BE48
2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20,:21:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55507
[ThaliCore] Session.disconnect() peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sBNOCkbXCebBBqCjmasHvifujgQgWVaq","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9571CE61-1016-4A87-8C94-F0E5DAB9C517
2017-07-20 2,0:21:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:49486480-D84F-4A41-91D2-46864F6A7584
[Thal,i,Core] Browser.startListening
2017-07-20 20:21:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:21:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 20:21:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
,2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"56B307C2-08AF-4A29-8560-B6A8AFB389FF","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B848E4-E7C9-4327,-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 56B307C2-08AF-4A29-8560-B6A8AFB389FF, (syncValue: RCbmvJl8phWwn0qfMtsRWkVY8DR04IjD)'
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56,B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","generation":0}'
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
2017-07-20 20:21:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E56D8C9C-324B-480C-8DDC-9842424945C0","generation":0}'
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:25 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
2017-07-20 20:21:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"17C71F8D-4817-4678-B647-BED88DB07F70","generation":0}'
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:25 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,6B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,6B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,6B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:56B307C2,-08AF-4A29-8560-B6A8AFB389FF error: max retries exceeded
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RCbmvJl8phWwn0qfMtsRWkVY8DR04IjD","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RCbmvJl8phWwn0qfMtsRWkVY8DR04IjD', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"56B307C2-08AF-4A29-8560-B6A8AFB389FF","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"56B307C2-08AF-4A29-8560-B6A8AFB389FF","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD (syncValue: 2qhJuWreOcmymPILpYqyKvuJTXEC0pfK)'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64,B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,4B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:21:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2qhJuWreOcmymPILpYqyKvuJTXEC0pfK","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:21:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2qhJuWreOcmymPILpYqyKvuJTXEC0pfK', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:21:38 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
,2017-07-20 20:21:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:21:38 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 20:21:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E56D8C9C-324B-480C-8DDC-9842424945C0 (syncValue: rVwnLFXFNlPJYAzph9IoFjv,oV39efJIm)'
2017-07-20 20:21:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E56D8C9C-324B-480C-8DDC-98424,24945C0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55524
2017-07-20 20:21:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rVwnLFXFNlPJYAzph9IoFjvoV39efJIm",,"error":null,"portNumber":55524}'
2017-07-20 20:21:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rVwnLFXFNlPJYAzph9IoFjvoV39efJIm', error: 'null', listeningPort: '55524''
,Connecting to the localhost:55524
,Connecting to the localhost:55524
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] TCPListener,.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
Connecting to the localhost:55524
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,Connected to the localhost:55524
,Connected to the localhost:55524
,Connected to the localhost:55524
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 92 correct string length
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 []
,ok 96 got the same data back
,# teardown
,2017-07-20 20:21:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:21:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9571CE61-1016-4A87-8C94-F0E5DAB9C517
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:E56D8C9C-324B-480C-8DDC-9842424945C0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55524
,[ThaliCore] Session.disconnect() peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4C94593B-EFAB-4A2A-BBD8-57221E91DD91
,2017-07-20 20:21:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FE8A022A-C2FA-4ABC-9A88-CDFF0F2C59AB
[ThaliCore] Browser.startListening
,2017-07-20 20:21:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:21:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:21:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
2017-07-20 20:21:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"17C71F8D-4817-4678-B647-BED88DB07F70","generation":0}'
2017-07-20 20:21:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 17C71F8D-4817-4678-B647-BED88DB07F70, (syncValue: 8HJdWpDUJuAtDLLxssi2Gg6jcaAQE8WU)'
2017-07-20 20:21:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB,07F70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) fou,nd peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
2017-07-20 20:21:43, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E56D8C9C-324B-480C-8DDC-9842424945C0","generation":0}'
,2017-07-20 20:21:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","generation":0}'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"749D76DB-9759-4DF1-9711-8D08EA81A735","generation":0}'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,7C71F8D-4817-4678-B647-BED88DB07F70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,7C71F8D-4817-4678-B647-BED88DB07F70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,7C71F8D-4817-4678-B647-BED88DB07F70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:17C71F8D,-4817-4678-B647-BED88DB07F70 error: max retries exceeded
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8HJdWpDUJuAtDLLxssi2Gg6jcaAQE8WU","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8HJdWpDUJuAtDLLxssi2Gg6jcaAQE8WU', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"17C71F8D-4817-4678-B647-BED88DB07F70","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"17C71F8D-4817-4678-B647-BED88DB07F70","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1 (syncValue: 39Fmopy,2dno1CpYtCFF1OBMGorBFC1iq)'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8976FF76-77A8,-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454
[ThaliCore] Advertiser: session connected Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40
[ThaliCore] Advertiser: session connected Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454
,[ThaliCore] Session.startOutputStream(with:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55543
,2017-07-20 20:21:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"39Fmopy2dno1CpYtCFF1OBMGorBFC1iq","error":null,"portNumber":55543}'
,2017-07-20 20:21:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '39Fmopy2dno1CpYtCFF1OBMGorBFC1iq', error: 'null', listeningPort: '55543''
,Connecting to the localhost:55543
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Server received psk id: psk-id
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:5
Connected to the localhost:55543
,[ThaliCore] VirtualSocket.closeStreams() vsID:5
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [6]
,2017-07-20 20:21:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40
,[ThaliCore] Session.session(_:peer:didChange:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40
[ThaliCore] Session.startOutputStream(with:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-20 20:21:59 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 20:21:59 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 20:21:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-20 20:21:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 20:21:59 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [6]
,2017-07-20 20:21:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 []
,2017-07-20 20:21:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4C94593B-EFAB-4A2A-BBD8-57221E91DD91
,[ThaliCore] Session.session(_:peer:didChange:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55543
[ThaliCore] Session.disconnect() p,eer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D98B737-989D-4AB0-BF85-D415CBA12454 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
[ThaliCore] Session.d,einit peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:085DE6E9-1621-4798-93C4-92CEA205E383
,2017-07-20 20:22:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE
[ThaliCore] Browser.startList,ening
2017-07-20 20:22:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:22:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:22:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
2017-07-20 20:22:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","generation":0}'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1, (syncValue: 4Peg8venW1RUdRoE55VrxtPL3nVvJcYw)'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7B,DD9E1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Browser,.browser(_:foundPeer:withDiscoveryInfo:) found peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTes,tUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0A4B69D-C26E-481F-B495-6814F733A0E6","generation":0}'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: ,'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"749D76DB-9759-4DF1-9711-8D08EA81A735","generation":0}'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","generation":0}'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:085DE6E9-1621-4798-93C4-92CEA205E383:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
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
,[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,76FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8976FF76,-77A8-4837-BB2A-DE6ED7BDD9E1 error: max retries exceeded
2017-07-20 20:22:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4Peg8venW1RUdRoE55VrxtPL3nVvJcYw","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:22:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4Peg8venW1RUdRoE55VrxtPL3nVvJcYw', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:22:12 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:22:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:22:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:22:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0A4B69D-C26E-481F-B495-6814F733A0E6 (syncValue: 18fKru5,C2xBtWvObwdojHdZiamr77mYB)'
2017-07-20 20:22:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0A4B69D-C26E,-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:22:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
,2017-07-20 20:22:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55560
2017-07-20 20:22:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18fKru5C2xBtWvObwdojHdZiamr77mYB",,"error":null,"portNumber":55560}'
2017-07-20 20:22:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '18fKru5C2xBtWvObwdojHdZiamr77mYB', error: 'null', listeningPort: '55560''
,Connecting to the localhost:55560
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
Connected to the localh,ost:55560
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,2017-07-20 20:22:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:22:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:085DE6E9-1621-4798-93C4-92CEA205E383
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D0A4B69D-C26E-481F-B495-6814F733A0E6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55560
[ThaliCore] Session.disconnect() p,eer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC544C48-D334-462B-8B12-0802DD7579AA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EC544C48-D334-462B-8B12-0802DD7579AA
2017-07-20 2,0:22:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F864AEC8-23D2-4A39-BC41-58D4FFEB0E08
[ThaliCore] Browser.startListening
2017-07,-20 20:22:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:22:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] AdvertiserManager,.stopAdvertising()
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] Advertiser.stopAdvertising() peerID:EC544C48-D334-462B-8B12-0802DD7579AA
2017-07-20 20:22:26 - DEBUG thaliM,obileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:22:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:22:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:22:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
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
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D1CE6BF1-D578-451B-A4E3-F581295AFA24
[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0ADC9EC4-02DD-44A2-B6A9-1445E4CE35DB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0ADC9EC4-02DD-44A2-B6A9-1445E4CE35DB
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0ADC9EC4-02DD-44A2-B6A9-1445E4CE35DB
,ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-20 20:22:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
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
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-20 20:22:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-20 20:22:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 20:22:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-20 20:22:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
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
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-20 20:22:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:0826aca4-ea60-497a-ab95-34f8176a7811 error: startListeningNotActive
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"ASlwdCli0iVegRPuO7cYjWoavuPjnBgk","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort ,is null
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0826aca4-ea60-497a-ab95-34f8176a7811","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:34 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0826aca4-ea60-497a-ab95-34f8176a781,1","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6E4A8421-580C-4F17-9E4A-CD9D304628A0
[ThaliCore] Browser.startListening
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on star,ting
ok 134 Got null as expected
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NSTEAqpwGuJaMHlytvOShQ2Zidf9kpLR","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:66777E41-AE6D-421B-AD9F-92AB273BE7FA
[ThaliCore] Browser.startListening
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:22:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on star,ting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
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
,[ThaliCore] BrowserManager.disconnect peer:8c5bee8c-b475-4d9f-a4c8-3efe95000537
,ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0635C8F3-9DF4-4970-BF0F-2DCA782B004F
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:22:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D8007DB7-899E-4F9C-BDCD-F0DF8263D741
[ThaliCore] Browser.startListening
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BB0751A3-27D6-4D76-8838-BBBBB43AF0C5","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B6B5F25-9D48-43DF-94FB-5D4582DB9155:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B6B5F25-9D48-43DF-94FB-5D4582DB9155", generation: 0)
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BB0751A3-27D6-4D76-8838-BBBBB43AF0C5 (syncValue: 3J57KITKrrUDrxTjhzVvIu5a0ZTqYrAu)'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B6B5F25-9D48-43DF-94FB-5D4582DB9155","generation":0}'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A5BDDF1-7B91-494B-BD51-A71449C556C9","generation":0}'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,B0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,B0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9B6B5F25-9D48-43DF-94FB-5D4582DB9155:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9B6B5F25-9D48-43DF-94FB-5D4582DB9155", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,B0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BB0751A3,-27D6-4D76-8838-BBBBB43AF0C5 error: max retries exceeded
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3J57KITKrrUDrxTjhzVvIu5a0ZTqYrAu","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3J57KITKrrUDrxTjhzVvIu5a0ZTqYrAu', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"BB0751A3-27D6-4D76-8838-BBBBB43AF0C5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BB0751A3-27D6-4D76-8838-BBBBB43AF0C5","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FEB23978-DEDA-4875-A80E-C75021896629 (syncValue: cJpLkqQ,ihac2uy3YZK7GL7V5xHgkQOZZ)'
2017-07-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:22:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55576
2017-07-20 20:22:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cJpLkqQihac2uy3YZK7GL7V5xHgkQOZZ",,"error":null,"portNumber":55576}'
2017-07-20 20:22:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cJpLkqQihac2uy3YZK7GL7V5xHgkQOZZ', error: 'null', listeningPort: '55576''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0) found active relay
,2017-07-20 20:22:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sQ9CCkxS80PEkktXFq5uGzws6RRJNd8w","error":null,"portNumber":55576}'
,ok 146 No error
ok 147 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0) found active relay
,2017-07-20 20:22:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"J6dQpnqN6i8p4klKpCOQ4hwdXkNuzsCc","error":null,"portNumber":55576}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-07-20 20:22:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:22:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:22:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:22:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0635C8F3-9DF4-4970-BF0F-2DCA782B004F
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FEB23978-DEDA-4875-A80E-C75021896629
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55576
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:9 [8]
,[ThaliCore] Session.disconnect() peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] BrowserRelay.deinit
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
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'listening 55579'
ok 151 Should throw
,# teardown
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'listening 55581'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:22:59 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 55584'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
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
2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 55588'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
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
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 55593'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
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
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'listening 55597'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'listening 55601'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'listening 55605'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-20 20:23:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'listening 55609'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
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
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'listening 55661'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'listening 55665'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:03 - DEBUG createNativeListener: 'listening 55668'
ok 198 port must be in range
,# teardown
,2017-07-20 20:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'listening 55669'
,ok 199 second start should return same port
,# teardown
,2017-07-20 20:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'listening 55671'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-20 20:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-20 20:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-20 20:23:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-20 20:23:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-20 20:23:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 55673
,ok 209 should be equal
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2
[ThaliCore] Browser.startListening
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"2A5BDDF1-7B91-494B-BD51-A71449C556C9","generation":0}'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A5BDDF1-7B91-494B-BD51-A71449C556C9 (syncValue: aDHpjMW11jXm1pNIqlz50esM97f6WzC8)'
2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A5B,DDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","generation":0}'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
2017-07-20 20:23:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","generation":0}'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","generation":0}'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2A5BDDF1,-7B91-494B-BD51-A71449C556C9 error: max retries exceeded
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aDHpjMW11jXm1pNIqlz50esM97f6WzC8","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aDHpjMW11jXm1pNIqlz50esM97f6WzC8', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"2A5BDDF1-7B91-494B-BD51-A71449C556C9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2A5BDDF1-7B91-494B-BD51-A71449C556C9","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FEB23978-DEDA-4875-A80E-C75021896629 (syncValue: 1Vy8bOM,fKBAxJgiIQKT5ngCUSiiabxCC)'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEB23978-DEDA,-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A
[ThaliCore] Advertiser: session connected Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A state: notConnected -> connecting
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A
,[ThaliCore] Session.session(_:peer:didChange:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,B23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE,B23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,B23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,EB23978-DEDA-4875-A80E-C75021896629", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,B23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FEB23978,-DEDA-4875-A80E-C75021896629 error: max retries exceeded
2017-07-20 20:23:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1Vy8bOMfKBAxJgiIQKT5ngCUSiiabxCC","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:23:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1Vy8bOMfKBAxJgiIQKT5ngCUSiiabxCC', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:23:26 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:23:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:23:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:23:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9B4A1C-33E8-444D-AF81-B5888BAC5468 (syncValue: Bx0lz3X,JAvpz5KN63HYVvbK7hHYdY1wx)'
2017-07-20 20:23:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD9B4A1C-33E8,-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55695
2017-07-20 20:23:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Bx0lz3XJAvpz5KN63HYVvbK7hHYdY1wx",,"error":null,"portNumber":55695}'
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Bx0lz3XJAvpz5KN63HYVvbK7hHYdY1wx', error: 'null', listeningPort: '55695''
,ok 212 should be equal
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F256E69-5A96-411E-9BF5-88677F81218D (syncValue: 0qsiWJ8j3Crlq5s2oT75zArXQpDmQVnF)'
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55699
,2017-07-20 20:23:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0qsiWJ8j3Crlq5s2oT75zArXQpDmQVnF","error":null,"portNumber":55699}'
,2017-07-20 20:23:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0qsiWJ8j3Crlq5s2oT75zArXQpDmQVnF', error: 'null', listeningPort: '55699''
,ok 213 should be equal
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
[ThaliCore] Advertiser: session connected Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
,[ThaliCore] Session.session(_:peer:didChange:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB
2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55695
[ThaliCore] Session.disconnect() peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:3F256E69-5A96-411E-9BF5-88677F81218D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55699
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
[ThaliCore] Advert,iserRelay.deinit
,2017-07-20 20:23:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0qsiWJ8j3Crlq5s2oT75zArXQpDmQVnF","error":"Session disconnected","portNumber":null}'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:1C9D3398-C78B-4A10-9D03-B59AD32B28CA
,# Multiple local http requests
,listening on 55701
,ok 214 should be equal
ok 215 should be equal
ok 216 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:23:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20, 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:369058E2-8F68-45CB-BB58-78A0C9B96289
2017-07-20 2,0:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2
[ThaliCore] Browser.startListening
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","generation":0}'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F256E69-5A96-411E-9BF5-88677F81218D (syncValue: wA9QDhiY70yDK46dh1IRr5hSdVUjRvL7)'
2017-07-20 20:23:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
2017-07-20 20:23:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","generation":0}'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "54E,FAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"54EFAE80-90BC-47EB-A297-F97D6E577012","generation":0}'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F256E69-5A96-411E-9BF5-88677F81218D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F256E69-5A96-411E-9BF5-88677F81218D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA
[ThaliCore] Advertiser: session connected Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F256E69-5A96-411E-9BF5-88677F81218D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:23:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wA9QDhiY70yDK46dh1IRr5hSdVUjRvL7","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:23:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wA9QDhiY70yDK46dh1IRr5hSdVUjRvL7', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:23:46 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 20:23:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 20:23:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 20:23:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-,07-20 20:23:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9B4A1C-33E8-444D-AF81-B5888BAC5468 (syncValue: iXEEG9VUMCZLrVJ27loTvIbCxutyKwaW)'
2017-07-20 20:23:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliC,ore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-,33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:23:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD,9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BD9B4A1C,-33E8-444D-AF81-B5888BAC5468 error: max retries exceeded
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iXEEG9VUMCZLrVJ27loTvIbCxutyKwaW","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iXEEG9VUMCZLrVJ27loTvIbCxutyKwaW', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BD9B4A1C-33E8-444D-AF81-B5888BAC5468","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:23:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E (syncValue: 2Hkx0qi,2EObq1hpqzPFzXpSXAWBb4GyH)'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA1C72E1-F0AA,-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84
[ThaliCore] Advertiser: session connected Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55725
,2017-07-20 20:23:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2Hkx0qi2EObq1hpqzPFzXpSXAWBb4GyH","error":null,"portNumber":55725}'
,2017-07-20 20:23:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2Hkx0qi2EObq1hpqzPFzXpSXAWBb4GyH', error: 'null', listeningPort: '55725''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-20 20:23:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 54EFAE80-90BC-47EB-A297-F97D6E577012 (syncValue: 1Lgg6yoAi1zsKTYSUuLUdL2ZgGMO5nrh)'
,2017-07-20 20:23:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-20 20:23:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84
,[ThaliCore] Session.session(_:peer:didChange:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55731
2017-07-20 20:24:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1Lgg6yoAi1zsKTYSUuLUdL2ZgGMO5nrh","error":null,"portN,umber":55731}'
,2017-07-20 20:24:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1Lgg6yoAi1zsKTYSUuLUdL2ZgGMO5nrh', error: 'null', listeningPort: '55731''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:24:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:369058E2-8F68-45CB-BB58-78A0C9B96289
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55725
[ThaliCore] Session.disconnect() p,eer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:54EFAE80-90BC-47EB-A297-F97D6E577012
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55731
,[ThaliCore] Session.disconnect() peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42561EB6-F4DC-4C01-835D-B30B08258B84
,[ThaliCore] Session.deinit peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 20:24:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] AdvertiserRelay.deinit
# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] Session.deinit peer:42561EB6-F4DC-4C01-835D-B30B08258B84
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
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
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'listening 55735'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'listening 55736'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EF25D641-9E77-42FF-BE90-E50B9720D431
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
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
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'listening 55737'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "86AB98C8-1A7B-4795-8C76-05AE6FE7BF1E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:86AB98C8-1A7B-4795-8C76-05AE6FE7BF1E
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "86AB98C8-1A7B-4795-8C76-05AE6FE7BF1E", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:86AB98C8-1A7B-4795-8C76-05AE6FE7BF1E
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:86AB98C8-1A7B-4795-8C76-05AE6FE7BF1E
[ThaliCore] Advertiser.stopAdvertising() peerID:86AB98C8-1A7B-4795-8C76-05AE6FE7BF1E
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
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
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'listening 55740'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 240 must be stopped
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
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,ok 243 specific error expected
,# teardown
,ok 244 must be stopped
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
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'listening 55741'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:208B2348-6081-4B07-94A5-F430EDECCC20
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7BAB9DAA-651F-4AD8-96B4-5DC8B80C4BD9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7BAB9DAA-651F-4AD8-96B4-5DC8B80C4BD9
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7BAB9DAA-651F-4AD8-96B4-5DC8B80C4BD9
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:09 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
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
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'listening 55744'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:36B5AA37-F5FE-4ECC-B26A-BBB5B5FC853F
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4133FB1-2F23-45F6-A76D-FACD1960E01E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F4133FB1-2F23-45F6-A76D-FACD1960E01E
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F4133FB1-2F23-45F6-A76D-FACD1960E01E
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-20 20:24:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 248 must be stopped
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
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'listening 55746'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:278682B3-E84B-4EBB-BAAE-6BCEEEA010DC
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C60A7EA8-786A-41BD-A609-86CBA47BE910", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C60A7EA8-786A-41BD-A609-86CBA47BE910
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C60A7EA8-786A-41BD-A609-86CBA47BE910
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
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
,ok 252 must be stopped
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
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-20 20:24:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
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
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
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
,ok 258 IMPLEMENT ME!!!!!!
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
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
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
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
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
,ok 262 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-20 20:24:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
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
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
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
,ok 266 must be stopped
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
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-20 20:24:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
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
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-20 20:24:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
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
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55749'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3B5C22A9-A49E-45CC-8129-D67CEE0EEE40
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C7,2E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:15 - DEBUG thaliMobileNat,iveWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273, advertisingActive matches
,2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55750'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C6B8FDF3-D1D9-4025-B450-03A8659E9B41", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C6B8FDF3-D1D9-4025-B450-03A8659E9B41
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C6B8FDF3-D1D9-4025-B450-03A8659E9B41
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 276 discoveryActive matches
,ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55752'
,# teardown
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
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
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 55753'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A74250C1-AAD0-44A0-AF25-AE84D320C411
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "534D867D-8D26-4A98-8194-F5DC97795695", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:534D867D-8D26-4A98-8194-F5DC97795695
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 279 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:534D867D-8D26-4A98-8194-F5DC97795695:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "534D867D-8D26-4A98-8194-F5DC97795695", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:534D867D-8D26-4A98-8194-F5DC97795695
2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 20:24:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-20 20:24:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-20 20:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 282 must be stopped
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
,ok 283 must be stopped
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
,# test to coordinate connection cut
,# teardown
,ok 284 must be stopped
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
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'listening 55755'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C504B930-A815-4606-B525-8D634ECAFF89
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CBE86867-1917-499E-88A8-9DE0439C821C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CBE86867-1917-499E-88A8-9DE0439C821C
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
2017-07-20 20:24:19 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E5D8D790-5AA9-,450B-BB53-D6A9AC6FC7F6", generation: 0)
2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}]'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}]'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E (syncValue: yNsPGB7lJMda41dmmpoifi4bO7xgS0a8)'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE86867-1917-499E-88A8-9DE0439C821C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE86867-1917-499E-88A8-9DE0439C821C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
2017-07-20 20:24:21 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}]'
2017-07-20 20:24:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","generation":0}'
,2017-07-20 20:24:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:24:21 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CA,1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,A1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:24:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yNsPGB7lJMda41dmmpoifi4bO7xgS0a8","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:24:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yNsPGB7lJMda41dmmpoifi4bO7xgS0a8', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:24:22 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:24:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 20:24:22 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:24:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E
2017-07-20 20:24:22 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
,2017-07-20 20:24:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 603D95D4-183F-4EC9-B17D-817535F98047 (syncValue: kAwZKyH6NPw8D5JJt4Ork3sPLIDHv0Vh)'
,2017-07-20 20:24:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55761
,2017-07-20 20:24:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kAwZKyH6NPw8D5JJt4Ork3sPLIDHv0Vh","error":null,"portNumber":55761}'
,2017-07-20 20:24:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kAwZKyH6NPw8D5JJt4Ork3sPLIDHv0Vh', error: 'null', listeningPort: '55761''
,2017-07-20 20:24:26 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:603D95D4-183F-4EC9-B17D-817535F98047:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [8, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:27 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:27 - DEBUG testUtils: 'Got end'
,ok 285 response body should match testData
,ok 286 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CBE86867-1917-499E-88A8-9DE0439C821C
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:603D95D4-183F-4EC9-B17D-817535F98047
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55761
[ThaliCore] VirtualSocket.closeStr,eams() vsID:10
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] Session.disconnect() peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:10 [8]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 288 FIX ME, PLEASE!!!
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-20 20:24:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 290 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 292 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 293 specific error should be returned
,# teardown
,2017-07-20 20:24:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:24:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'listening 55763'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 305 error should be null
,ok 306 error should be null
,# setup
,ok 307 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'listening 55764'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:76DF78C4-28DE-4609-A4E9-B8E545389EA0
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
ok 311 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
# teardown
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}]'
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","generation":0}'
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"603D95D4-183F-4EC9-B17D-817535F98047","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 error should be null
,ok 313 error should be null
,# setup
,ok 314 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'listening 55765'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D8208D0C-53F3-4796-A725-B762046DB804", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:D8208D0C-53F3-4796-A725-B762046DB804
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D8208D0C-53F3-4796-A725-B762046DB804", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:D8208D0C-53F3-4796-A725-B762046DB804
20,17-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 317 error should be null
ok 318 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D8208D0C-53F3-4796-A725-B762046DB804
,[ThaliCore] Advertiser.stopAdvertising() peerID:D8208D0C-53F3-4796-A725-B762046DB804
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 319 error should be null
,ok 320 error should be null
,# setup
,ok 321 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'listening 55768'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 326 error should be null
,ok 327 error should be null
,# setup
,ok 328 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-20 20:24:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 329 This should not cause wifi to fail
,ok 330 native router should be bad
,# teardown
,ok 331 error should be null
,ok 332 error should be null
,# setup
,ok 333 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'listening 55769'
,ok 334 first call should succeed
ok 335 first call should succeed
ok 336 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 337 error should be null
,ok 338 error should be null
,# setup
,ok 339 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-20 20:24:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 340 error should be null
,ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-20 20:24:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 343 error should be null
ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-20 20:24:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e1035d2-4320-4576-8393-0d1536a8ab7b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 346 should be called once
,ok 347 should not have been called more than once
,# teardown
,2017-07-20 20:24:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5e1035d2-4320-4576-8393-0d1536a8ab7b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 348 error should be null
ok 349 error should be null
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
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"61c86583-fa1e-4838-af78-444e77578fa2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 356 peer should be available
,ok 357 cache contains native peer
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"61c86583-fa1e-4838-af78-444e77578fa2","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 358 peer should be unavailable
,ok 359 peer has been removed from cache
,# teardown
,ok 360 error should be null
,ok 361 error should be null
,# setup
,ok 362 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 363 we have not added peer to the cache yet
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05615e74-53f7-41ec-8346-7c0c1d8adbe0","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 364 peer should be available
,ok 365 cache contains wifi peer
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05615e74-53f7-41ec-8346-7c0c1d8adbe0","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 366 peer should be unavailable
,ok 367 peer has been removed from cache
,# teardown
,ok 368 error should be null
,ok 369 error should be null
,# setup
,ok 370 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f73f75bf-2a98-4dcb-86e8-ded1fb9f52fd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 371 first peer is a,vailable
2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"02ef9ca6-8776-40f4-8aba-99cfe774e6dc","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 372 second, peer is available
ok 373 first and second peers are different
,# teardown
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f73f75bf-2a98-4dcb-86e8-ded1fb9f52fd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"02ef9ca6-8776-40f4-8aba-99cfe774e6dc","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 374 error should be null
ok 375 error should be null
,# setup
,ok 376 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 377 should not be in cache at start
2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec3de536-1913-4555-ad4d-31c521d6aafe","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 378 peer is available
,# teardown
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ec3de536-1913-4555-ad4d-31c521d6aafe","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 379 error should be null
ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-20 20:24:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 382 error should be null
ok 383 error should be null
,# setup
,ok 384 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-20 20:24:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 385 error should be null
ok 386 error should be null
,# setup
,ok 387 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b2f159f-3855-4f2d-8643-0e35f2b3030f","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 388 peer should be ,available
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b2f159f-3855-4f2d-8643-0e35f2b3030f","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 389 peer should be available
,ok 390 should store correct generation
,# teardown
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2b2f159f-3855-4f2d-8643-0e35f2b3030f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 391 error should be null
,ok 392 error should be null
,# setup
,ok 393 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'listening 55770'
2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"557e1cfd-d080-418e-8bf1-e2e48ec3e6f3","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 394 discovered correct peer
ok 395 got correct generation
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"557e1cfd-d080-418e-8bf1-e2e48ec3e6f3","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 396 discovered correct peer
ok 397 got correct generation
,# teardown
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"557e1cfd-d080-418e-8bf1-e2e48ec3e6f3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 398 error should be null
,ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'listening 55771'
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2fbc1f48-0b11-4e1a-9f63-128a23b4975f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 401 discovered available peer
,ok 402 peer is available
,# teardown
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2fbc1f48-0b11-4e1a-9f63-128a23b4975f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 403 error should be null
ok 404 error should be null
,# setup
,ok 405 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f238398e-5cf1-4959-a432-7c2bac67130d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 406 peer should be ,available
2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f238398e-5cf1-4959-a432-7c2bac67130d","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 407 peer, should be unavailable
ok 408 should be removed from cache
,# teardown
,ok 409 error should be null
,ok 410 error should be null
,# setup
,ok 411 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'listening 55772'
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e83840af-2fee-4d5e-a306-e68a79a6332b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 first peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e1ade15e-4e19-4992-8b09-846c55e0cc59","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 413 second peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e1ade15e-4e19-4992-8b09-846c55e0cc59","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e1ade15e-4e19-4992-8b09-846c55e0cc59","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 416 we found peer again
,ok 417 it was wifi peer
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e1ade15e-4e19-4992-8b09-846c55e0cc59","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 418 peer became unavailable
,ok 419 it was wifi peer
,# teardown
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e83840af-2fee-4d5e-a306-e68a79a6332b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-20 20:24:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 423 error should be null
,ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'listening 55773'
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3266b132-6069-465e-af52-3fb55a2b0f65","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 426 first peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"74201b5a-3e50-4b6b-ae17-f170266461ec","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 427 second peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3266b132-6069-465e-af52-3fb55a2b0f65","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 428 peer became unavailable
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"74201b5a-3e50-4b6b-ae17-f170266461ec","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:41 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 430 error should be null
,ok 431 error should be null
,# setup
,ok 432 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-20 20:24:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 433 error should be null
,ok 434 error should be null
,# setup
,ok 435 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-20 20:24:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 436 error should be null
,ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1aef6a99-2f8e-4089-9500-49c4530a99ec","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 439 peer discovered first time does not have new address
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1aef6a99-2f8e-4089-9500-49c4530a99ec","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 440 address has not been changed
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1aef6a99-2f8e-4089-9500-49c4530a99ec","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 441 new port handled correctly
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1aef6a99-2f8e-4089-9500-49c4530a99ec","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 442 new host handled correctly
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1aef6a99-2f8e-4089-9500-49c4530a99ec","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 443 newAddressPort is null for unavailable peers
,# teardown
,ok 444 error should be null
,ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-20 20:24:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-20 20:24:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 457 should be equal
,# teardown
,ok 458 error should be null
ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-20 20:24:43 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 461 error should be null
ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-20 20:24:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 464 contains expected properties
ok 465 the same hostAddress
ok 466 the same portNumber
,# teardown
,2017-07-20 20:24:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 467 error should be null
,ok 468 error should be null
,# setup
,ok 469 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 470 contains expected properties
ok 471 the same hos,tAddress
,ok 472 the same portNumber
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 473 error should be null
ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'listening 55774'
2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5a303d9-7f17-4620-8e8e-1d9d419d46fb","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
,ok 476 Got specific error message
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c5a303d9-7f17-4620-8e8e-1d9d419d46fb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 477 error should be null
,ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'listening 55775'
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"929be0dc-eecf-4d57-bb05-0ea84743364a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:929be0dc-eecf-4d57-bb05-0ea84743364a
,ok 480 native wrapper `disconnect` called once
,ok 481 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"929be0dc-eecf-4d57-bb05-0ea84743364a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 482 error should be null
,ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 485 error should be null
ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 488 error should be null
,ok 489 error should be null
,# setup
,ok 490 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 491 error should be null
ok 492 error should be null
,# setup
,ok 493 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 494 error should be null
,ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 497 error should be null
,ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-20 20:24:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 500 error should be null
ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-20 20:24:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 503 error should be null
ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'listening 55776'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DA402F1E-0DBA-4492-A5F5-AB64495DEED0
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2698fdf6-8e49-4836-ba38-0e808fe10c9f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 Peer availabilities has one entry for our connection type
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9b70376-e8df-4dc7-920e-76412b04073e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 507 Peer availabilities has one entry for our connection type
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2698fdf6-8e49-4836-ba38-0e808fe10c9f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b9b70376-e8df-4dc7-920e-76412b04073e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 508 No peers
,ok 509 No peers
,ok 510 No peers
,# teardown
,ok 511 error should be null
,ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'listening 55777'
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fda94448-51d8-4cfe-9e4e-ed8724cb24a8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 514 1
,ok 515 2
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4dcd32fb-8d72-499f-a725-d7b9a29d56b5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fda94448-51d8-4cfe-9e4e-ed8724cb24a8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4dcd32fb-8d72-499f-a725-d7b9a29d56b5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 516 error should be null
,ok 517 error should be null
,# setup
,ok 518 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-20 20:24:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 519 error should be null
,ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'listening 55778'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:640FCAA2-E8A9-419B-A56C-205453BA21D8
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 524 error should be null
,ok 525 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 526 error should be null
ok 527 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
2017-07-20 20:24:49 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","generation":0}]'
2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","peerAvai,l,able":true,"generation":0,"portNumber":null}'
2017-07-20 20:24:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C2BF93C0-656C-4565-8E64-9D866559AD79 (syncValue: 0)'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","generation":0}]'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","generation":0}'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55781
2017-07-20 20:24:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":55781}'
,2017-07-20 20:24:52 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67C489F9-6AF1-4BB0-8C69-0EC08B235189 (syncValue: 1)'
2017-07-20 20:24:52 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [8, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:53 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:53 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
[ThaliCore] Advertiser: session connected Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
[ThaliCore] Advertiser: session connected Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55785
,2017-07-20 20:24:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":55785}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [8, 11, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:56 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:56 - DEBUG testUtils: 'Got end'
,ok 528 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
,[ThaliCore] Session.session(_:peer:didChange:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
[ThaliCore] Session.startOutputStream(with:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [8, 11, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
[ThaliCore] Session.startOutputStream(with:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [8, 11, 12, 13, 14]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:25:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C2BF93C0-656C-4565-8E64-9D866559AD79","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:25:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:640FCAA2-E8A9-419B-A56C-205453BA21D8
,2017-07-20 20:25:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:25:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-20 20:25:00 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:25:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:25:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 20:25:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeS,treams() vsID:13
,ok 529 error should be null
ok 530 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeS,treams() vsID:14
,# setup
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [8, 11, 12, 14]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [8, 11, 12]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[Th,aliCore] VirtualSocket.deinit vsID:12 [8, 11]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:11 [8]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, c,ount:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 531 ThaliMobile should be stopped
,# test for data corruption
,2017-07-20 20:25:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
,2017-07-20 20:25:01 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 542 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-20 20:25:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
,ok 586 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 587 is an agent
ok 588 enqueue is fine
,ok 589 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 590 is an agent
ok 591 first enqueue is fine
ok 592 is an agent
ok 593 second enqueue is fine
ok 594 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 595 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 596 is an agent
,ok 597 good enqueue
,ok 598 Identity should match
,2017-07-20 20:25:07 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:25:07 - DEBUG testUtils: 'Got end'
,ok 599 Got expected response
,ok 600 Got psk call back
,# teardown
,2017-07-20 20:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 601 is an agent
,ok 602 enqueue worked
,ok 603 is an agent
,ok 604 enqueue 2 worked
,ok 605 enqueue is not available when stopped
,ok 606 start action is killed
,ok 607 killed action is still killed
,ok 608 enqueued action when stopped is killed
,ok 609 inQueue is empty
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
,ok 629 2nd good enqueue
,ok 630 1st action is in the pool
,ok 631 2nd action is in the pool
,ok 632 1st action is out of the pool
,ok 633 2st action is out of the pool
,ok 634 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-20 20:25:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 635 Got right error
,ok 636 Start should not be called
,ok 637 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 20:25:11 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 638 Got right error
ok 639 Start should not be called
ok 640 Kill should have been calle,d at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 641 Got null
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 642 is an agent
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 643 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 644 Got Null
,ok 645 Got another null
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 646 is an agent
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 647 is an agent
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 648 Action 1 killed at least once
,ok 649 Action 1 went first
,ok 650 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 651 should have gotten null
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 652 Should have stopped nicely
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 653 Still looking for null
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 654 Yup, another null
,ok 655 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 656 Null 1
ok 657 (unnamed assert)
2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 658 is an agent
,ok 659 Null 3
ok 660 Replication not yet called
,ok 661 Notification 2 not yet called
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 662 is an agent
,ok 663 Notification went first
,ok 664 Notification 2 not called yet
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 665 is an agent
,ok 666 Notification finished
,ok 667 Replication finished
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 668 is an agent
ok 669 First does not throw
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 670 is an agent
ok 671 Second does not throw
2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 first ok
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 674 is an agent
,ok 675 second ok
,ok 676 third ok
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
,ok 677 peerIdentifier should match
,ok 678 generation should match
,ok 679 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 680 good beacon
,ok 681 good preAmble
,ok 682 public keys match!
,ok 683 must return null after successful call
,ok 684 Once start returns the action should be in KILLED state
,# teardown
,2017-07-20 20:25:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-20 20:25:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-20 20:25:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 685 Response should be NETWORK_PROBLEM
ok 686 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-20 20:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 687 Resolution should be BAD_PEER
ok 688 correct error message
,# teardown
,2017-07-20 20:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 689 Call start once
,ok 690 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 691 must return null after successful call.
,# teardown
,2017-07-20 20:25:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 692 Should be Killed
ok 693 Start after killed
,# teardown
,2017-07-20 20:25:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-20 20:25:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 696 Should be KILLED
ok 697 must return null after successful kill
,# teardown
,2017-07-20 20:25:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 698 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 699 must return null after successful call
,# teardown
,2017-07-20 20:25:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-20 20:25:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 700 Should be NETWORK_PROBLEM caused closing server socket
,ok 701 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 702 Should be NETWORK_PROBLEM caused closing client socket
ok 703 Should be Could not establish TCP connection
,# teardown
,2017-07-20 20:25:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 704 publicKeysToNotify cannot be null
,ok 705 ecdh for local device cannot be null
ok 706 milliseconds cannot be less than 0
,ok 707 milliseconds cannot be 0
,ok 708 milliseconds cannot be greater than one_day
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
,2017-07-20 20:25:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
,ok 734 keys match
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
ok 745 bluetooth peer's notification has correct connection type
ok 746 tcp peer's notification has correct connection type
,2017-07-20 20:25:37 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-20 20:25:37 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 20:25:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 747 notification peer dictionary contains exactly 1 peer
2017-07-20 20:25:38 - WARN thaliNotificationClient: 'peer is not available'
ok 748 notification peer dictionary does not contain any peers
2017-07-20 20:25:38 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 20:25:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 749 entry exists
,ok 750 entry is resolved
,# teardown
,2017-07-20 20:25:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 751 Action should be KILLED
,ok 752 Peer state should be RESOLVED
,# teardown
,2017-07-20 20:25:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 753 hostAddress must match
ok 754 portNumber must match
,ok 755 suggestedTCPTimeout must match
,ok 756 connectionType must match
,ok 757 peerIDs must match
,# teardown
,2017-07-20 20:25:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 758 Correct error
,# teardown
,2017-07-20 20:25:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 759 hostAddress must match
,ok 760 portNumber must match
,ok 761 suggestedTCPTimeout must match
,ok 762 connectionType must match
,ok 763 peerIds must match
,# teardown
,2017-07-20 20:25:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-20 20:25:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 20:25:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 765 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 20:25:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 766 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 20:25:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 action should be resolved with NETWORK_PROBLEM error
ok 768 correct number of requests
ok 769 correct number of failures
ok 770 correct final peer state
,# teardown
,2017-07-20 20:25:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-20 20:25:45 - WARN thaliNotificationClient: 'peer is not available'
2017-07-20 20:25:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 771 peerDictionary should become empty
,# teardown
,2017-07-20 20:25:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-20 20:25:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 failed with expected error
ok 773 peer state should be RESOLVED
,# teardown
,2017-07-20 20:25:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-20 20:25:46 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 774 First action failed
,ok 775 second action killed
,# teardown
,2017-07-20 20:25:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 776 secrets are equal
ok 777 Public key matches with the server key
,ok 778 hostAddress must match
,ok 779 portNumber must match
,ok 780 suggestedTCPTimeout must match
,ok 781 connectionType must match
,# teardown
,2017-07-20 20:25:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 782 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 783 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-20 20:25:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 785 All keys need to be available in the cache
,ok 786 All entries should be expired after 1 second
# teardown
,2017-07-20 20:25:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 787 Size of the cache should be 2
ok 788 Cache doesn't contain dictionary1
,ok 789 Size of the cache should be 1
ok 790 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-20 20:25:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 791 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 792 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-20 20:25:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,ok 794 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 795 no error
,ok 796 should be 204
,# teardown
,2017-07-20 20:25:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 797 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 20:25:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 798 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 20:25:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 799 no error
ok 800 should be 200
,ok 801 should be equal
,ok 802 should be equal
,ok 803 (unnamed assert)
,ok 804 no error
ok 805 should be 204
,# teardown
,2017-07-20 20:25:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 806 error should be null
ok 807 should be 204
,# teardown
,2017-07-20 20:25:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 808 should be 404
,# teardown
,2017-07-20 20:25:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 809 equal keys
ok 810 not equal connection type
ok 811 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-20 20:25:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 813 second cleared dictionary
,2017-07-20 20:25:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 814 First start and on called correctly
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
,2017-07-20 20:25:59 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-20 20:25:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-20 20:25:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-20 20:26:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:26:00 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-20 20:26:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 849 right error
,# teardown
,2017-07-20 20:26:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-20 20:26:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-20 20:26:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 850 right error
,# teardown
,2017-07-20 20:26:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-20 20:26:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 852 Got error as expected
,# teardown
,2017-07-20 20:26:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-20 20:26:03 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-20 20:26:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 853 Got error as expected
,# teardown
,2017-07-20 20:26:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-20 20:26:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-20 20:26:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-20 20:26:12 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:12 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 856 should be equal
ok 857 All tests passed!
,# teardown
,2017-07-20 20:26:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-20 20:26:16 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 20:26:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 858 action should be killed
ok 859 Error should be timed out
,ok 860 No doc found
,# teardown
,2017-07-20 20:26:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-20 20:26:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 861 should be equal
,2017-07-20 20:26:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 20:26:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 862 action should be killed
,ok 863 Error should be timed out
,# teardown
,2017-07-20 20:26:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 864 socket hung up
,# teardown
,2017-07-20 20:26:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 865 same getPeerAdvertisesDataForUs
ok 866 Same pouchdB
ok 867 same localDbName
ok 868 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-20 20:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'listening 55914'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Browser.startListening
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A89418E0-73C5-49E6-9EE7-B3AAB0664285
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}]'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 2)'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F,90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Advertiser: session connected Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE state: notConnected -> connecting
[ThaliCore] Se,ssion.init(session:identifier:connected:notConnected:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Advertiser: session connected Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}]'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55917
,2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":55917}'
,2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 3)'
,2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.session(_:peer:didChange:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [8, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [8, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [8, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [8, 16, 17]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [8, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [8, 16, 17, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:19 [8, 16, 17, 18]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [8, 16, 17, 18, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [8, 16, 17, 18, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [8, 16, 17, 18, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-20 20:26:32 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [8, 16, 17, 18, 20, 21, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [8, 16, 17, 18, 20, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30, 31, 32]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.s,tartOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-20 20:26:32 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30, 31, 33]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
,[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 30, 31, 33]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:30 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 33]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,4 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 33]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 33, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 33, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 35, 36]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
,[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TC,PClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55943
,2017-07-20 20:26:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":55943}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 37]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 37, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:34 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [8, 16, 17, 18, 20, 21, 22, 23, 24, 25, 26, 28, 31, 37, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [8, 16, 17, 18, 21, 22, 23, 24, 25, 26, 28, 31, 37, 39, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [8, 16, 17, 18, 21, 22, 24, 25, 26, 28, 31, 37, 39, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [8, 16, 17, 18, 21, 22, 25, 26, 28, 31, 37, 39, 40]
[ThaliCore] VirtualSocket.handleEv,entOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [8, 16, 17, 18, 21, 25, 26, 28, 31, 37, 39, 40]
[ThaliCore] TCPClient.socketDid,Disconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [8, 16, 17, 21, 25, 26, 28, 31, 37, 39, 40]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [8, 16, 17, 21, 26, 28, 31, 37, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31,
[ThaliCore] VirtualSocket.deinit vsID:31 [8, 16, 17, 21, 26, 28, 37, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Thal,iCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:28 [8, 16, 17, 21, 26, 37, 39, 40]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [8, 16, 17, 21, 26, 37, 39, 40, 41]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [8, 16, 17, 21, 26, 37, 39, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [8, 16, 17, 21, 26, 37, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [8, 16, 17, 21, 26, 37, 39, 40, 41, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [8, 16, 17, 21, 26, 37, 40, 41, 42, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:40
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:40 [8, 16, 17, 21, 26, 37, 41, 42, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [8, 16, 17, 21, 26, 37, 41, 43, 44]
,2017-07-20 20:26:35 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [8, 16, 17, 21, 26, 37, 41, 44]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [8, 16, 17, 26, 37, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [8, 16, 26, 37, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [8, 16, 37, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
,[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [8, 16, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [8, 16, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cl,ient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A89418E0-73C5-49E6-9EE7-B3AAB0664285
,2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:26:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIde,ntifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:26:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 20:26:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:26:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:26:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [8, 16]
,ok 869 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'listening 55951'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EB94D05F-0832-4170-8059-233820381033
,[ThaliCore] Browser.startListening
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:086240B2-409F-45A5-A6CA-A35C459065A0
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [8, 16, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [8, 16]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}]'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}]'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 4)'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) found active relay
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":55943}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 5)'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) found active relay
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":55917}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [8, 16, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:46 [8, 16]
,2017-07-20 20:26:37 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [8, 16, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [8, 16]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:37 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [8, 16, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [8, 16]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [8, 16, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 6)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":55917}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [8, 16, 49, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:50 [8, 16, 49]
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 7)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":55943}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [8, 16, 49, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [8, 16, 49]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocket,DisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,2 [8, 16, 49, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [8, 16, 49]
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 8)'
2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) found active relay
2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":55917}'
[Th,aliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [,8, 16, 49, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [8, 16, 49]
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [8, 16, 49, 54]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:54 [8, 16, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 9)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) found active relay
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [8, 16, 49, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [8, 16, 49]
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":55943}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [8, 16, 49, 56]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}]'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5E079B7C-5E99-4561-83E0-A4660711AA6F (syncValue: 10)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[Th,aliCore] VirtualSocket.deinit vsID:56 [8, 16, 49]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDis,connectHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","generation":0}]'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","generation":0}'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] Advertiser: session connected Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
,[ThaliCore] Session.startOutputStream(with:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [8, 16, 49, 57]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NSLocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [8, 16, 49]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55967
2017-07-20 20:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":55967}'
,2017-07-20 20:26:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 671A5B41-0FE3-43CA-96C3-FB13B9B80FEC (syncValue: 11)'
,2017-07-20 20:26:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [8, 16, 49, 58]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:58
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [8, 16, 49]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [8, 16, 49, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:41 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-20 20:26:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 870 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:59 [8, 16, 49]
,[ThaliCore] Session.session(_:peer:didChange:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
,[ThaliCore] Session.session(_:peer:didChange:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] Session.startOutputStream(with:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [8, 16, 49, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55943
[ThaliCore] Session.disconnect() peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] VirtualSocket.deinit vsID:60 [8, 16, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] Session.startOutputStream(with:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [8, 16, 49, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.deinit peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}]'
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}'
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:26:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:42 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
,[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:61 [8, 16, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.did,SocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] Advertiser: session connected Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.deinit peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55917
[ThaliCore] Session.disconnect() peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}]'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","generation":0}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-20 20:26:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:44 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55973
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":55973}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3F90916C-93B2-4AEA-A154-B951CA01BF30 (syncValue: 12)'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":"Peer is unavailable","portNumber":null}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 13)'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":"Peer is unavailable","portNumber":null}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-20 20:26:44 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'han,dlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3F90916C-93B2-4AEA-A154-B951CA01BF30","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:3F90916C-93B2-4AEA-A154-B951CA01BF30
,[ThaliCore] BrowserManager.disconnect peer:B3A4F582-40E9-402A-9159-D09698B7BF1C
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [8, 16, 49, 62]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] VirtualSocket.deinit vsID:62 [8, 16, 49]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [8, 16, 49, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-20 20:26:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 871 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
,[ThaliCore] VirtualSocket.deinit vsID:63 [8, 16, 49]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
,[ThaliCore] Session.session(_:peer:didChange:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] Session.startOutputStream(with:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [8, 16, 49, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] Session.startOutputStream(with:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] VirtualSocket exited RunLoop vsID:64
,[ThaliCore] VirtualSocket.deinit vsID:64 [8, 16, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [8, 16, 49, 65]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:65
,[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
,[ThaliCore] VirtualSocket.deinit vsID:65 [8, 16, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:086240B2-409F-45A5-A6CA-A35C459065A0
,2017-07-20 20:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:26:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:26:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 20:26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [8, 16]
,2017-07-20 20:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:26:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 872 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 873 should throw
,ok 874 should throw
,ok 875 (unnamed assert)
,ok 876 (unnamed assert)
,ok 877 (unnamed assert)
,ok 878 (unnamed assert)
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
# teardown
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
,ok 892 (unnamed assert)
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
,2017-07-20 20:27:05 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:09 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 950 verify failed
ok 951 constructor called once
,ok 952 constructor called with right args
ok 953 start before stop
ok 954 We got at least 3 calls to start
ok 955 at least 3
ok 956 default 1
ok 957 1 run
ok 958 default 2
ok 959 2 run
ok 960 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 961 start out null
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 962 back to null
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 970 verify failed
,ok 971 constructor called once
,ok 972 constructor called with right args
,ok 973 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-20 20:27:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 974 verify failed
ok 975 constructor called once
,ok 976 constructor called with right args
,ok 977 (unnamed assert)
,ok 978 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-20 20:27:14 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 979 verify failed
,ok 980 constructor called once
,ok 981 constructor called with right args
,ok 982 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-20 20:27:15 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 983 verify failed
,ok 984 constructor called once
,ok 985 constructor called with right args
,ok 986 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 987 should be equal
ok 988 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-20 20:27:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:27:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 989 Got right error
,# teardown
,2017-07-20 20:27:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-20 20:27:16 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 990 Got socket hang up
,# teardown
,2017-07-20 20:27:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-20 20:27:17 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 991 Got 500 as expected
,# teardown
,2017-07-20 20:27:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-07-20 20:27:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 994 should be equal
,ok 995 revs are equal
,# teardown
,2017-07-20 20:27:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 996 should be equal
,ok 997 revs are equal
,ok 998 should be equal
,ok 999 revs are equal
,ok 1000 should be equal
,ok 1001 revs are equal
,# teardown
,2017-07-20 20:27:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/9,A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/9A91191F-,0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-20 20:27:24 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1002 Our rev is old so we should fail
,# teardown
,2017-07-20 20:27:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1003 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/9,A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/9A91191F-,0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-20 20:27:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-20 20:27:25 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1004 stop caused us to fail
,ok 1005 We specifically failed on a stop before put
,# teardown
,2017-07-20 20:27:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1006 failed due to stop
,ok 1007 failed due to stop
,# teardown
,2017-07-20 20:27:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1008 should be equal
,# teardown
,2017-07-20 20:27:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-20 20:27:29 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1009 Expected bad seq error
,# teardown
,2017-07-20 20:27:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1010 Different promises
,ok 1011 Timer was cancelled
,ok 1012 should be equal
,# teardown
,2017-07-20 20:27:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1013 One go and one blocked
,ok 1014 All blocked
,ok 1015 Still blocked
,ok 1016 should be equal
,# teardown
,2017-07-20 20:27:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1017 We waited long enough
,ok 1018 should be equal
,# teardown
,2017-07-20 20:27:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1019 Should have gotten same timer promise
,ok 1020 Still same timer promise
,ok 1021 We waited long enough
,ok 1022 should be equal
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
,ok 1023 expressPouchDB was called once
,ok 1024 expressPouchDB was called with 2 arguments
,ok 1025 expressPouchDB was called with 'PouchDB' as 1-st argument
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
,[ThaliCore] Session.startOutputStream(with:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [8, 16, 66]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:66
,[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
,[ThaliCore] VirtualSocket.deinit vsID:66 [8, 16]
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
,2017-07-20 20:27:41 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:41 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'listening 56048'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D312A872-2798-4E40-BA44-0168E839B29F
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0,
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
,2017-07-20 20:27:41 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D16EEE39-8D79-4E45-BF1C-5DDAFFF50A46", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D16EEE39-8D79-4E45-BF1C-5DDAFFF50A46
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:27:41 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}]'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:27:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5E079B7C-5E99-4561-83E0-A4660711AA6F (syncValue: 14)'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0) found active relay
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":55967}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [8, 16, 67]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:67
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:67
,[ThaliCore] VirtualSocket.deinit vsID:67 [8, 16]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:27:41 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
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
,2017-07-20 20:27:41 - DEBUG thaliManager: 'stopping everything'
,2017-07-20 20:27:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D16EEE39-8D79-4E45-BF1C-5DDAFFF50A46
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1063 ThaliMobile.stop was called once
,ok 1064 ThaliMobile.stop was called with 0 arguments
,ok 1065 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1066 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1067 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1068 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 56051'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70C98B8F-34D5-477D-8081-1CBE67D98242
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "533CB0CF-07FD-4280-93DF-1161E97BC597", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:533CB0CF-07FD-4280-93DF-1161E97BC597
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:533CB0CF-07FD-4280-93DF-1161E97BC597
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 20:27:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1109 ThaliMobile.stop was called once
,ok 1110 ThaliMobile.stop was called with 0 arguments
,ok 1111 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1112 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1113 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1114 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'listening 56053'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0FA417FE-A4ED-4498-A8D8-AE09CC98CA56
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EDD018B7-C633-4E70-80C0-50EEB951FF17", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EDD018B7-C633-4E70-80C0-50EEB951FF17
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EDD018B7-C633-4E70-80C0-50EEB951FF17
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
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
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'listening 56055'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:50C3C68E-4A91-4AEB-904B-17B66D4889AB
,[ThaliCore] Browser.startListening
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
2017-07-20 20:27:43 - DEBUG t,haliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18BB11BD-67A3-46C4-AFB3-E32CCAC6701B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:18BB11BD-67A3-46C4-AFB3-E32CCAC6701B
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:18BB11BD-67A3-46C4-AFB3-E32CCAC6701B
2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:27:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}]'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5E079B7C-5E99-4561-83E0-A4660711AA6F","generation":0}'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'listening 56057'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25456E27-51E1-4BDF-A570-20BBD1B0BE8D
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75C0D997-8EA9-4CA5-B1F5-E55265C51BBF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:75C0D997-8EA9-4CA5-B1F5-E55265C51BBF
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:75C0D997-8EA9-4CA5-B1F5-E55265C51BBF
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
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReache,d handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
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
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We prope,rly fire peer unavailable and then available when connection fails on iOS'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying, to connect make sure recreate does not happen'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER r,esult: passed - #stop should change peers'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
2017-07-20 20:27:44 ,- INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
2017-07-20 20:27:44 - INFO Coordinated,Client: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
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
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:285:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-,B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exp,orts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/A,pplication/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore,/node_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-0,7-20 20:27:44 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-20 20:30:44 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-20 20:30:45 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-20 20:30:45 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-20 20:30:45 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www,/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/9A91191F-0476-4581-ADCD-B32165B4E62C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-20 20:30:45 - DEBUG, CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
