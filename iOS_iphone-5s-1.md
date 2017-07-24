#### Test 113351851dc08641_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/DCD48375-2ABE-4923-95A3-643B789F0222/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DCD48375-2ABE-4923-95A3-643B789F0222/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49610"
,(lldb)     command script import "/tmp/DCD48375-2ABE-4923-95A3-643B789F0222/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-07-24 06:49:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:49:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:49:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:49:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:49:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:49:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:49:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B158D5C9-E12E-41B7-A98F-C69C7E3179B7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B158D5C9-E12E-41B7-A98F-C69C7E3179B7
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:124E4E3C-C44A-4013-AB1F-53FD64E1C20D
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] ,BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C40D1F2C-324C-439B-ABC4-69CF249D2450
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort,:errorHandler:) Peer(uuid: "DA644B64-A3B7-4F51-BC10-F01AF50AB648", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DA644B64-A3B7-4F51-BC10-F01AF50AB648
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA644B64-A3B7-4F51-BC10-F01AF50AB648:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA644B64-A3B7-4F51-BC10-F01AF50AB648", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-24 06:49:22 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.683371007442474
,2017-07-24 06:49:22 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-24 06:49:22 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DA644B64-A3B7-4F51-BC10-F01AF50AB648:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DA644B64-A3B7-4F51-BC10-F01AF50AB648", generation: 0)
,2017-07-24 06:49:25 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 06:49:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 06:49:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 06:49:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 06:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 06:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 06:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 06:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 06:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 06:49:29 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 06:49:29 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 06:49:29 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 06:49:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-24 06:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 06:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
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
2017-07-24 06:49:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-24 06:49:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-24 06:50:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 06:50:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AADC6A1D-CC00-49FE-A24A-0CBD0454AF4A
[ThaliCore] Browser.startListening
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:50:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:77E6D906-68A9-4036-8788-CE8A81E82840
[ThaliCore] Browser.startListening
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ADB366EC-0AE8-4274-AD5A-3E49680FA024", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ADB366EC-0AE8-4274-AD5A-3E49680FA024
2017-07-24 0,6:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ADB366EC-0AE8-4274-AD5A-3E49680FA024
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "42920242-D9D2-44AB-A74C-0C3106633885", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:42920242-D9D2-44AB-A74C-0C3106633885
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:05, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(,onPort:errorHandler:) Peer(uuid: "42920242-D9D2-44AB-A74C-0C3106633885", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:42920242-D9D2-44AB-A74C-0C3106633885
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:42920242-D9D2-44AB-A74C-0C3106633885
,[ThaliCore] Advertiser.stopAdvertising() peerID:42920242-D9D2-44AB-A74C-0C3106633885
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1B872D94-0E3D-47EC-A5CB-D9C2E6EF2258
[ThaliCore] Browser.startListening
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6A12CD7D-7950-4B6B-B5CF-8B3408D52793:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6A12CD7D-7950-4B6B-B5CF-8B3408D52793", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D4AD769C-CE08-4F9C-9F77-256A14CEDA92
2017-07-24 0,6:50:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A
[Thal,i,Core] Browser.startListening
,2017-07-24 06:50:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:50:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A764879-3CA2-4857-9907-8F7C5858454B
[ThaliCore] Advertiser: session connected Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2A764879-3CA2-4857-9907-8F7C5858454B state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F9DFD667-2284-45B8-A906-89AA2F28FD1E
[ThaliCore] Advertiser: session connected Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F9DFD667-2284-45B8-A906-89AA2F28FD1E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
2017-07-24 06:50:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A8B1D4F7-116E-489E-90A9-6E13E0070383","generation":0}'
2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A8B1D4F7-116E-489E-90A9-6E13E0070383 (syncValue: O2vYxu0bAUqsSrkJaEw4sfZD3Wqe3bkl)'
2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E00,70383", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
,2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","generation":0}'
2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F9DFD667-2284-45B8-A906-89AA2F28FD1E
,[ThaliCore] Session.session(_:peer:didChange:) peer:F9DFD667-2284-45B8-A906-89AA2F28FD1E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A764879-3CA2-4857-9907-8F7C5858454B
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A764879-3CA2-4857-9907-8F7C5858454B state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59753
,2017-07-24 06:50:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"O2vYxu0bAUqsSrkJaEw4sfZD3Wqe3bkl","error":null,"portNumber":59753}'
,2017-07-24 06:50:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'O2vYxu0bAUqsSrkJaEw4sfZD3Wqe3bkl', error: 'null', listeningPort: '59753''
,2017-07-24 06:50:21 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-24 06:50:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D4AD769C-CE08-4F9C-9F77-256A14CEDA92
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:A8B1D4F7-116E-489E-90A9-6E13E0070383
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59753
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"O2vYxu0bAUqsSrkJaEw4sfZD3Wqe3bkl","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8B1D4F7-116E-489E-90A9-6E13E0070383","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8B1D4F7-116E-489E-90A9-6E13E0070383","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A764879-3CA2-4857-9907-8F7C5858454B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F9DFD667-2284-45B8-A906-89AA2F28FD1E
,[ThaliCore] Session.deinit peer:F9DFD667-2284-45B8-A906-89AA2F28FD1E
[ThaliCore] AdvertiserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:83026883-B6BD-420E-91E3-BE6D772339D8
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15
[ThaliCore] Browser.startListening
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
2017-07-24 06:50:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
2017-07,-24 06:50:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1E6B3DB7-E302-4E55-B5BA-67F66946C1AC (syncValue: T0yX0CJTQEnkhgigbgcNJZYxSQ9f6seU)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E007038,3", generation: 0)
2017-07-24 06:50:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0) creati,ng a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A8B1D4F7-116E-489E-90A9-6E13E0070383","generation":0}'
2017-07-24 06:50:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,24 06:50:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
2017-07-24 06:50:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A44","generation":0}'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:27 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"90E5B58F-B1BF-40A1-8EAA-0CEFE86BBF,C0","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:27 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Session.deinit peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Session.deinit peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E,6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1E6B3DB7,-E302-4E55-B5BA-67F66946C1AC error: max retries exceeded
2017-07-24 06:50:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"T0yX0CJTQEnkhgigbgcNJZYxSQ9f6seU","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:50:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'T0yX0CJTQEnkhgigbgcNJZYxSQ9f6seU', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:50:37 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:50:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 06:50:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 06:50:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:50:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 281373AD-3A04-4E63-8025-EA0CD6FB0A44 (syncValue: FQrjf3H,IuyMwcDZYKf9uhkTVf6cjpQKD)'
,2017-07-24 06:50:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-24 06:50:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59759
2017-07-24 06:50:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FQrjf3HIuyMwcDZYKf9uhkTVf6cjpQKD",,"error":null,"portNumber":59759}'
2017-07-24 06:50:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FQrjf3HIuyMwcDZYKf9uhkTVf6cjpQKD', error: 'null', listeningPort: '59759''
,Connecting to the localhost:59759
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,Connected to the localhost:59759
,2017-07-24 06:50:40 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,2017-07-24 06:50:40 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:1
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,ok 88 got the same data back
,# teardown
,2017-07-24 06:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:83026883-B6BD-420E-91E3-B,E6D772339D8
2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59759
,[ThaliCore] Session.disconnect() peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FEC221C2-D82C-4FE9-8F21-083998DFCE02
2017-07-24 0,6:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] Browser.startListening
2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-24 06:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
2017-07-24 06:50:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0","generation":0}'
2017-07-24 06:50:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0, (syncValue: 47ONjfKg0HnVxcsFSdBHE3nJxd56LF1b)'
2017-07-24 06:50:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86,BBFC0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
2017-07-24 06:50:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A44","generation":0}'
,2017-07-24 06:50:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","generation":0}'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","generation":0}'
2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:90,E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,0E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:90,E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,0E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:50:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"47ONjfKg0HnVxcsFSdBHE3nJxd56LF1b","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:50:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '47ONjfKg0HnVxcsFSdBHE3nJxd56LF1b', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:50:52 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:50:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
,2017-07-24 06:50:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 06:50:52 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:52 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:50:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7DC295B6-5886-44D5-B750-7B97D55E9F06 (syncValue: zMxkBiUOeqRvUhfxCQpLFuR,U2iaX5AFA)'
2017-07-24 06:50:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7DC295B6-5886-44D5-B750-7B97D,55E9F06:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:50:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59774
2017-07-24 06:50:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zMxkBiUOeqRvUhfxCQpLFuRU2iaX5AFA",,"error":null,"portNumber":59774}'
2017-07-24 06:50:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zMxkBiUOeqRvUhfxCQpLFuRU2iaX5AFA', error: 'null', listeningPort: '59774''
,Connecting to the localhost:59774
,Connecting to the localhost:59774
Connecting to the localhost:59774
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
Connected to the localhost:59774
,Connected to the localhost:59774
,[ThaliCore] Session.startOutputStream(with:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,Connected to the localhost:59774
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2, 3]
,ok 96 got the same data back
,# teardown
,2017-07-24 06:50:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:FEC221C2-D82C-4FE9-8F21-083998DFCE02
2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06,:,50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:59774
[ThaliCore] Session.disconnect() peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliC,ore] BrowserManager.disconnect peer:7DC295B6-5886-44D5-B750-7B97D55E9F06
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zMxkBiUOeqRvUhfxCQpLFuRU2iaX5AFA","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE
,2017-07-24 06:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC
[ThaliCore] Browser.startListening
2017-07-24 06:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-07-24 06:50:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
2017-07-24 06:50:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","generation":0}'
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C64B7CA2-74CB-48B1-B1C0-43A726C4E62F, (syncValue: Pumxj4KCP8ZpffD33QC0Zrl9Lrd514Uj)'
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C,4E62F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","generation":0}'
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD,63EEF5F","generation":0}'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45717B12-6A7B-4A44-B673-96CD3521F8C0","generation":0}'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,4B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C64B7CA2,-74CB-48B1-B1C0-43A726C4E62F error: max retries exceeded
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Pumxj4KCP8ZpffD33QC0Zrl9Lrd514Uj","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Pumxj4KCP8ZpffD33QC0Zrl9Lrd514Uj', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F (syncValue: FUg24wd,uoVOTpytzTfcA1YxfIBIJZ0ys)'
2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664
[ThaliCore] Advertiser: session connected Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59792
,2017-07-24 06:51:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FUg24wduoVOTpytzTfcA1YxfIBIJZ0ys","error":null,"portNumber":59792}'
,2017-07-24 06:51:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FUg24wduoVOTpytzTfcA1YxfIBIJZ0ys', error: 'null', listeningPort: '59792''
,Connecting to the localhost:59792
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:59792
,2017-07-24 06:51:13 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 06:51:13 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
# teardown
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664
[ThaliCore] Session.startOutputStream(with:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 3, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 06:51:15 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 06:51:15 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 06:51:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 06:51:15 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-24 06:51:15 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1278CD6B-3495-487E-91D3-B225D2EA3365
[ThaliCore] Advertiser: session connected Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1278CD6B-3495-487E-91D3-B225D2EA3365 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1278CD6B-3495-487E-91D3-B225D2EA3365
,[ThaliCore] Session.session(_:peer:didChange:) peer:1278CD6B-3495-487E-91D3-B225D2EA3365 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1278CD6B-3495-487E-91D3-B225D2EA3365
,[ThaliCore] Session.startOutputStream(with:) peer:1278CD6B-3495-487E-91D3-B225D2EA3365
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 6, 7]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 06:51:18 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 06:51:18 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 06:51:18 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 06:51:18 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 06:51:18 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [2, 3, 6]
,2017-07-24 06:51:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1278CD6B-3495-487E-91D3-B225D2EA3365 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1278CD6B-3495-487E-91D3-B225D2EA3365
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59792
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FUg24wduoVOTpytzTfcA1YxfIBIJZ0ys","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:1278CD6B-3495-487E-91D3-B225D2EA3365
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C
,[ThaliCore] Browser.startListening
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F","generation":0}'
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F (syncValue: eSnGaZCvYAbuh8x8ZGxueI1T0rNy4CMy)'
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
2017-07-24 06:51:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","generation":0}'
2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:21 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
2017-07-24 06:51:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}'
2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:22 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,A05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,A05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,A05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,A05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5CA05EEE,-49A1-4649-9CDD-C17AD63EEF5F error: max retries exceeded
2017-07-24 06:51:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eSnGaZCvYAbuh8x8ZGxueI1T0rNy4CMy","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:51:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eSnGaZCvYAbuh8x8ZGxueI1T0rNy4CMy', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:51:31 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:51:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 06:51:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 06:51:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:51:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3720624C-71F8-4A6E-A942-2A1B9013449F (syncValue: 0c5PJ3e,NWBcDmV9igtSWmMP5QRGUhBXV)'
2017-07-24 06:51:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3720624C-71F8,-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:51:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109
[ThaliCore] Advertiser: session connected Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59810
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0c5PJ3eNWBcDmV9igtSWmMP5QRGUhBXV","error":null,"portNumber":59810}'
,2017-07-24 06:51:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0c5PJ3eNWBcDmV9igtSWmMP5QRGUhBXV', error: 'null', listeningPort: '59810''
,Connecting to the localhost:59810
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
,Connected to the localhost:59810
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 3, 6, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:8 [2, 3, 6]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109
,[ThaliCore] Session.session(_:peer:didChange:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109
[ThaliCore] Session.startOutputStream(with:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [2, 3, 6, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (4167 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (34076 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received (5393 bytes):'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server received all data: TUa7bx0R9oKM9HTVn2kIbX7UoKQg34jMOVhdCx1j3E7Y0fxzubQkMIyvFYI7GUu5EeOqjX8Pjp3vEFobWaQp3x0Bq3FjNxBcJD5Dczc8CrfK7ilb13XQ1VmDfDLM7cJUMi6LNOgNVhyBd9OFjzVk6yPXM6cNhOo4h3D8eNUyxk4tAI8W5xMq7dOPjVEedPCM3mGBhf2pzwWA3MRDEAmHd1WxOyfPY8YZ7O7RDZ7QGdmfNJ3efECoa2WkYlOWTuhPHdQOJ2L8wzQ2git0Hc65X1enqotmqeD5HYAAnodjDqO1fvOKYv1Z2koNC8MH86BeBShmQwkb8lwm09A2qQuXG2JxJHA3YneqiQKjV5iMeyOCY67jSvYb28nEF4A8pU0RLHdZyacIakxuQowXI6q2rCz0edRrC8L86O241YHzq3OATCzCDf,h5KM3URtQjO3fXybT1DoVDRlv81gs2aIlZeBnKSS5aTsrxRnBIvQT5HGZmLwKSRcwSjhdWxy9PMIuiEwmQ01ZyuSPsxp8YTu21T7uTwKVEIdB3OFDuGHQcFCVSDdvoQPSARaAylJgHQmUQo9XMBwt9P3criyn2OwqOUZ9tiNaqlQArkpb7V7TgETxRlbmfgr04JWij0QLnvaWcskNN4kJ5W16Af7YppOHPKKAbAKnffZoMZLJnQB3eJvkJs3uwFSSghJGNFPhN1TDEvflUASlJnpaEQENmjLkWljOFYFk8a06rrhSKcRogPnKC31vxKP3YRvWAGgLSjl8CepVdgnN5EFSflgtntszlsSz449czGN5MWOSCKnJ8BQKgHXZgBjudhirSb7qU04AX4RMzmSQkeZunePwHjVNrm6hm2E8UAffPV2y3GKCY5PvvF35P5BUIXION8pujFJ6sk7lljKQ7Ai6Gn2UYAve6nsnZQUyTvInQ8KiqsfSqWlZixCwRVhqIxpMYwfflTmvzfcdr8aalATZDqphiaogzjVgDNAaH2HKEP0PsEiFZSaXyocuG2rJyC3t0o1H6Cj7EJuuIr2vg95E4RFCIRptdFXCpvgr0YF9b48UwC6CXNwwPB5kz6yygS0LqWpQ3yeWOgqhaz4zcjbF6ZE1I4VarHYNnjCu2Ks0YtBNjJwDwOBAjIwZNLQrlCKfD0fRzbGIcHMgZhgZCCQVadLKvfEFvtdaVC19vAU8Hmg5iWfNh9tP078Kp2c,ozEES9uMkVipBEmw3B1PLoVE2tRx312z7u6yijpahBSIZdyAEN1mJZUeroJ7CcSDhJmJikTTP7KRirEvGWQr9HReiEAG4mMEd8HYUXHpPVhqvqMlpMOf4m2Pv17RCDn3706v21YHp6vH19KEPTz5L1N0hXLTeLmIDTb1aEpFHK13D1SFtOzpSrm00JZLL4nl0YWR9RzugxxuxTqZJHfnI0tUflXAVhbdpDnzBrKIC7ehjwXB0Wcx7OSYHJ9YXuoh,HPyeyPTJ7VuCIGlqXdmdGxWoEcI8ByUUsghImipMRsioeDvdC7nkKtSWxqZxtFdjqAcSVVydNV4HX2BdxJQQ1arstVujAPrG5lVpOjJC6zFlWJW8J0KktlkUaDgO0PFekQdZiZ07dBCzq7JRXQxRSBKnZxo5XeobmnBZ0p2OKJG2Qu6AWOIZJ4ICcf5NzrvkI2jOpFe6qCTuF698xyP6X9erhWDILfb5sdSAnuJQdJoxAWNF0mzX4nOpV4CB2YMn,vJhzfZEvPfOz2fC52Qn8sZIecR1nD7t9ak0zPmlL9zje2WXjwnS1T34fxi7QYaFKxwr6F2gfUML5HfM3bgV0CxtG9zk00WPae1eHx8yLA2AZX8gzjQn8JFYVfkfAtXzrkQECHrA5iiP6m7dvCt0l7tgu12Sx1qQCo3yUUCpQJO0fb4E4T47UjUxJXE2ufMtSQY1D71VeZSoBkFOGJqh0sqXl4cApm0UeDOG3eyMPqCbMtadqUFEqsZOdqH39NsG2,bww2b7ue4tLwEhuyyPifxTVKL1B5dPxTJDaSYSPnxt4J9Pdm9wRenqqdsYz4xmnnw03OxRa4BBD4XvYkqwnaEjMw8TCbqJNHzjBYJFglStlutRbVCW9rpYF5W8FjYdUN62Tj3U2YLa5yRklXhIGasHvIdIRV5Gi5O9OziOVM6hKcMk7OUreWY0LD6RpuQU2ehVYhG3VXn4xNViaec8Iq7yxGYwWyA8vE5JhoLUCZeEfH7kSMPZKiH5iQKJNDLbof,I7r4neQbp8M2EtH6aQY1kBreOXKf0jypjF8cmGQjJM1afeFTeEM0XvhNx2HhR0aMAxReVGfrzVeuN1iYCyd9nqjZqeyMf5vjQ4MEPcAJmkVJBK6HCdOTdq8DUMZREvS6L98F8OyJTO13JSjR8HK3ERk7ZIDA6JqJSrDErlXyDnlHTcQzdHd2xt9qwMalRispO21z5H16Mi2gDYqeUSxSArIr0QQdlat3QdOqLOxtRSECBYNgpSHVymjhSEKOb36t,GGLs6jEFgWUubes327cgQLlAeugJqtYA5LZdIDfwbIzK4ok2UjTgdXlQduI198WOa9B5RWMVQ3P5Vnwp4vEbem1RZfCUNguB1opyvN13t015pSYAtlhAc3oMhgxCk0e8L4alTaKtVHTOU3jT6Q8qyU15ncnKYUvg5Y3OpGoz9nVfwxJXqw82MS9qNnoetrMisxuXxmWB82hxa2wTfy33p7sca4iee5rcNYS5ucaXFEcltZfAyEvXqFRQzkDnlKVS,BABUUVQlL0g4nAl89gWLFg9a5YUmfQGhw0TeeHDLFKCGi4B69NTwDE2xTDgGhjz3y1Otig2LTInp2uTzeg1cilNZneDS9ylR74snp0uSzMy6ysk54GV0vOkUfFF2SmNcmr2VLNkDN2egcJ7HPoxjh2TGGeMFMdkIwhx2LHt4NDU8nbEvBaog2mDOtnH32GBXhbXdPAunajXLgqVwVRcoEM3uPaHq7AYwXU60RxDswvclwPEaNsDknNHvoyXdLbWt,dYEy49NcxrmIIFIsiD7dkmEYHwpxlg0b3bTZAJ4xLHQwfBal5kpS4KZCPTOiguTEfa69NZF6NqsqaMuruKRC3n3r1hrz0cN8Tiyen3I9z4WgMuuYMlxiu80Bd8axguVI2keQ7Ff3nh8O4TLe5fCMNJEGs9i8W8l45D2eMOgbxdvHQ4nEmdFMIpe9TTQ6IK5QaSfaET1IXbxDehHZfYWZkHAN7A31jfrf3T6WWSjaDWGOxiSBiRJUEeBRdfIHrryp,5lgIZisIW8w5dJVDb7WrUPleLQ3r1POrzHfmOK6qEMF2PqXyX2e6RVQUXBXZbZbdmTBhaaBlQsCkdpI4f3BKk6VD7OeRmkPqQLhCw3kjMmYuYKUF5Kop1tnd1xCZVdoM6FkGuoOLt5J1m7IGN7GYeeMkYPaZ89nlLrHb8aE53ScBCNVqM0o9FR1wvaKIcVKdjnJtYA3ZlnOMxOgwyLN9wvtIvmY6RfSMxVTfu2uM4rA6WMFw3ROZGvKNYknA7smh,ta3XrKLfDQU1btV3smTevTyDfqwylJ4DHCAIwrSAjQlog5aBKbplRm1UOff1HIiCIIA9fZfKAlrMdQ3laP0o4crPH1mGdDmk0xuMKLfjPtTUnXoJ1mQIV2XyPagCJSgiYUXsznY0s0z0rqHaOh2UbjY0FF99h9HAuKOobLmfMjxfed32YoZaigCDOq0UxrItOwG0R4CHFqnSSoQsZLm3D7Pyb3f3DJJCELUR35SBUpHFDTFfT7boaOQBZFqaMNkV,YO53qFw2StKQBn3copAcTrszmMGzWbeIqil1IyP9ucoF0Mm0GarS2TApJ0bDzl21iQHLtCbYVRrzpWqgFSpcvhXaomLc47smYP5ruEH90igSl205w41A9zSRACB0dAaf0T3iZtPItfV3zmJdYvd6z8TSoxrYFR3NFraoYW2twDfxeDCN5As7saKP5QUwfe22BZX2Ph42gLR732cq3Y63QcTT1UicwJLVJMXNykADoIefYYv5Kh6ditfCD7x8dz3S,BUcZLzljYI520DcoYaZ2LQVScTfoNY3RMvZKh8kRjAJmzppo0ITTdYW1keFkmECE0wnRZELFx8ZOLIhGFHlxMSjjKUaqcZNhmnvCPlM9RtHho1NtP5mHlnpwhW0Rm5Nu3yr9Qfj7FizmkInneou8O0tfc0WJxAosdXgDL4vioZM7YzXXm1y2DvSefXXlJKHEOnG0TDAavtH2Cb9ymwHiKT4kTkzwsD3Meg6sm82aMEikYywshIXQfAgizWGDQGgO,3Ob3Li8aSlJUsDUE0xQcLK2Hg19WKX7C01scYzmVzyWoT1VYNK7E2h7cJ5sN1mExJIZ8XPeTCw9sc2qtpy3VO8UAwBa5EsFrKqNftlcGHVprQYbqF706PX6gEd87t7AJ9lBPQFxmfEjvYspLk5Q6VQm14TcoJpSdHxlV6tNxAxmgVjJQtUlJRYTBV1qhPhUwd7Tm558JEdRJDbfqJBW4mfeJBEVEuDMNS9q2T2pwbTPc2LfRvGBn4A5LUu8FJayN,rXHcBv42e1Iiap4UQlHbSbSlbN0kq8I8kIBF0fFlBbnsxhCMA2JIGbRXTkdpquHRLVVwFlepTh1IQZKfX7a56PXgVTxLCGDsBs9OvEcjcYHuC7aynKchnTcEb86e6HiJEhDTRn4lWq5eUT7HTAR93R6mdx150lfPKLh2bIqqi3MHmOvoH8SxJfubvABljjvS3nPIxqKO9unnMEZieehswKpMv9vGJ86ySGmfmU89m1IMHj6xn0eU1Azvtpyi9kCq,NbQpPzMkReLcGvoXJTdnIjSKfYmV9YUSph5K5SqJSFXvVMLLFcBXLmhs8tH8iOanbK15cNfGzmsKfXEHMenC9eHe6Jy0dWgAyxbbYsoW2js5UyVEiznumwCmWDmPD4LH9Ootqd7GUMv8Lnm9o7xrDuFeX3eKpEPUQktESn10jVsEnxX0hJOYpIxPbCwvqZzxzUFZKY3IGCTyGrxobY6eghyhXTl2XDHj6wElkx4NkdZsQUUcRww2YYyf8ojX47DE,IHBy6YRa2bOZOXmu48OHd1UL7BDEtPK7eZfb0PzKqoiOOhgFJrIfMhYAeI9sKXRa49pVidJTrG6nSXFQW35EFjnOPWGU2mi329nRp7SnlIwkSHl9yNTLTtL6IyrMMaTghUCBwzr3LtyKeUmgET1A4F1kJejbOdyekQmDwKzVyuvrgyAo3wqvkdzuAJAXMpoDwiH8GtKbUUSqxkdv2NkqDjk9WEIvIo3ccg1SusjPLyvnrNHWGrQafzO2SVzTjgCD,TQvdppMmARhzXKGUBYTtOil6bgUii4pyBKOkosJHnCx5hVOQW0uE67ljnxV8nJWKp3zZt4r7PJDmkcsGPMtDeVjV05P5dBDERmx1OIRlEqGC2AVxTVvpmpjj6BTzNwz53VjQYZi9bJEzTXScKH8qQn3ZPoycuOKTBMZl4chBQNiPvQNsOfR5ef66ns04TLFjIsYusjvfZWSbnuOVQRXXT4eBHIPglXQvCjoNffBOsOna2wjqJObjTf4ScmLAlAVo,X5nTLKnOUxxbSt8IHyPOAHk00J6Ix9VP8LK2Z8RODd0KPxmCqCqLUyjtSXNUJhQDexKuEHgo3RyfoafaJfXqN1n5xForxQg0W24MpY7vCyqZN9JBBYkzOF5IqzeIph2yrfgTwjGcPbn9PBv4HrAqvCXFa7O1b2Il56HRcqgHt48twujD7SfStYpTEXvGFsxhcU7V6uos1xRCrENHqpwOEYC6ig6wyPRfqjSJC7EEXfLI3uxmqMfpS0dzfg5fLzzJ,yWGo0rkLAKW5wXuEWoT4sCXEpmYR4GlLbNWwUpoAyWwKuChHpc0greSnfM6h0jHCMHR6qu8Xyu1gGqAGOoctAe03kJHl84EssuSn3bOBgbU5D6PjHgLPtsPUZibwkMntX9T1V9hWLLPK7Hm2eiRyyYT0DdBkdOEJXXSnEJE38vVrHLJ8LeGYtU7DEt1nMlJwjgHGIEkzEjfoLSS4snjm6To7EoQUTKwVCvkiypOMo8ce0QeIHfYWvTRS3dv5GiOL,pf6aMTA8QQ8I3zqaUJsIQjvfToOHSvsslYIzfEvVvmGRYJX2XaYAtLgSSSd7E6ax2tZ2o4EJhqtLKyStgNDK39lVTPzwu0ZKuqfEp6tuIfyfMEE6um7OCSHWzI65Q2lDZR6RRj9OSY8KnaXNqUnyb7dFuy7QsJW1oDt67uiDnIPEWN5bexKYFPmgYlwAJjWL725WKLEdOO3V3gzMCLgiUfKoubJho4yk80nX0Iq7aK78BYOBaaSbQxFsHwTTxqWr,VL0HfLRR5xvuSYzE5pzmKQ8ilvMlaj9Xr7lPjayodCYGd9Cgld9g82wkjnkEzxUJzB60nZ7EHx93mKFiTEBWKtuOAFyOZHs5YK60ot4B8mvWDMIfioWG4fxlsBEam2xV8fV5JajA3EoTBCBkN7VvRQE60wGP4oeJsgedZxWmLvStqVjNmbCLoGwlkPpgImjrduz7BOFLjU9N5Vr88jYgAP6lskVFQAHZVgolGsyJL0mypVio6cD6nf8PxHIeACfa,hC7TFuYo99hOjSyHVD1kFIJJUmKvorEirkf3OmKxpGzZ4BKUsMs7TQxxXw8uPpnFaNYTIN8ma0HlQMNpxTan9rEfKNn6rmg1C6I4gUEiN6jK73YL5w2clJ5QIE2IH7mSxbuKsOGLLxtD9HwsXektKcJZswcDePy1dQvLvdm68f3C1tF7VTncD7gbEoAaBpaw7LK6MvpPpFZzDYIX5ZqlMjByGcut9p9QRzjqZ2WMZNOUkUtmwoRxM1mXHEavW1xp,w4AfYNMKynAsdXuBdsS33tlVxqHtxJ6jLDFZsrVt2UeQ2F4rXh9tB7zSC6lvlEpg3MIKFT9c4TVSYpF4UhRfjVP8oZ1ebKn7DUaznviOFUnlnsEK6M2t7ClRG3I2nD66S6pf9q6A56pwoSezZuw1RoxpUq7EoN1lNItUafFNs0CxCRGiAYsBxQT4kWeuEgPwyAu4tvsZZE9woHcWnG1UZQiIDbhV3MGEIVNrlVZV4TVcPLe4NmsRatYt93ii0IiR,DbGm53OtRKBZ2fu68Jg4fPchc77LYxBewUN177mzgnoF00lQsexV51PtjdF6Cziyjj5JiT4DelcTpkoEi0M1BA9rjCyTxznTmA6MIbGfaeWhHRRpqNNWiuM92O7xuYsWzpQmsALmdT1yVBGSxxu6ickrU7CS6buVKh07DRE0Yqp6dRKyWIxgVPFhWAebW3s7W6axXhnv3bqaYyltpLD99FRP34ZnJYaq4kruFOMqIJ6MU1f5MpqRQxPGsw0T222h,ZJZjJTsexqCvE9PpzP7LrDyfBIhdbDlhSGR6OLzQSIIhswI5WfgGWNqjYvbtXAU7v2zKsAnYsSxM94u3OUfrBrWAIqlv8us43ttrcAFPhQv2vNzYzEl8gO7bgHpKAPJ02aBquOLf4KYfu8kK6DlTm0l8JJQtdN9szbqXlVN780KO4SOYhH2SmToDUuV6J3OERoiq8Hx7nZ9gTQgZO9t6OkVFTVKL58JDuL6uPeTvvZ0wPAK5wMKxzxvjkpyB3aO7,N0MwpLVLasXT3MMf0XEPklBeBvFNBePptm0CNWLF8XERxPfRIKnQKoy9XMQobbfyBgcgzPCTOV3CaBbIiAwU3tY0ZgvVOVvRQ0AtZeOJiaoroTa1EUD7q0YdfviAUzXuopEo0x7hLNeF1udGCXBvLfKGADf0VVBLtAs8CqHOU55GIjcTzm16fPeUgsFDWbueCVHuiqEz7pTmzM0qIKJFzjSBJhYLulC2Xgofehd9KM9H2wdXXEFNMa8RC4j3VPLu,agDcOFY23DpxyFexEW1jzzYzWnA8CCplj90CTjFnpqFLVeu81jVZOcGZ7Ye0o2y4uU98KJXsGhGWphrEDr871HDJbcjfHtBuuBlg7MXXUH6Zn944p48680Fr6hQcWHIODWPce6uE9VYz5kWs338DKYSOWn8spZdywzKOBxEztVZEV9idJwDKcTfQ9BJSBUcy54V998F1gxZ64KVkqTmd95lWCzsOzokG1xkI8VmA7rGRGBDZ0lUN1kkRQN4CyDET,AXUFvoNFN0Cof78U4AEO4ZeePJZz24XQTXkx57tILOhRI7p0Ax8ZzJmURyFch8YDd6A1pPWVtoBABhA7TJvWsG7W820NOghyETgibpBlshKhtg9xENpd6QK2vWCnxA9mACtERsMvP5IFllsELeadCkNqBFQG0tqcG639TMxk7tWHOOpXT8ib6MF8dPmQ8yOmNW6se42axrRV1A7lIiW76T6hu9sxnliub32Q0DObq2uq45nmwrhlHPTT1pvEp88K,PDfHoOROfzrYzOR69jXrCcg1p4Q4KfArInp4cX5TD9S9BG21PJ1fsjdpmRcodJot3czrni4pMqRtewKuE0m3grw0RpBvqjNazrDizurOzhxmYdNKkPk2AEoUg2HHMo9GJSGg0T8HiQ9TgVWGwai3otaIoSSQQGNmG3yB9CMqUjaGrBPpDjlqSP4QgPHqd5g7wCJ8YFNaXtOvdqZsPj1oS3UXQfCn2MZzz0iZtEOqegUX2I1JsdpjFUNnjwg0v2pd,OlDI7izLbeyYgNoC55eJPny3KGzHGPC0qJzseuo1RZNFnZHWwT8SCVlimIzDhKBcDZC8mE1UtQ10wzMTYia3IuIYw4kvxQ1Nl5OsKSb69JiUdBVoWBaiT2GAVesuUxjRNUlZNm6PybpCNHlxyvInovZ3DicEX6Idb9biP34i7J3RAFZBFeAqTT0jI2YpvTWnNQkAdwW9ERqAgdIkfMSV75HMDirIkOOF2QKzIEVCxG4uWfDCx01ITOP9onCsI35P,S2HaHpJnD7I1OfU1C0YjYI36tU3zVHcigyj5VdBKaeC7Pi4uUe5t4szByqqfMD0P0DQf0xPcKa5LbUmRPcCkNuHyAavQPrz2SJsopf5ILBaID5skJBSS8ISXvbjuD8QwsWO4Kl3Y8lCNA6ghwWpY7uFLmi8NFVCgmeyAkFOdQsNe1kxXvSqDmeGlKWVVEBiaIzaAPvf15sTJUmLaLIoZXRycoEnrKbeDVRFDimblfaNwRHTGKq950JzyRjOlAI03,qfDzscEMgbK4vl2iSEkDAdBvdM3JGdEKu0kItryrhnB64yXlaoxXYoWYEaZcDv7PPxobzr3rtlp8xynONQcCFIYXkHkgMqy2u0rFotFzTrowB9rVUL8c9vw6ouiMnnIj4VzijvwtA6JV8vVbOhGnpFAOjCfj7oRHKOsfrhQk5RK72G7nsicoRvW613tYsr2hRu63pnNYUQnbKrVGjPbkRzBp9UYczrAAvxRCurA2fTx93ydrIOxCsCXIdj6hDoL2,aljRyzFpIMVqQ4ZMDCcNqyKppRftDAI5zMHz2XdkN59qIvc7GHcg4TYXnlru4iIeC5YPCxoIEIB3vxjcrCsscHw1pTSuM5JdnaWAfTf1lRT6WQj5EU144b6eU1olXNNGzAH8aVHR1m5mjrHrAJJVx5Rp3UTjosEOPNPoL8fnQvNEZ0ScnZTNFCy4QIYYayXSlBJ68idQ1lhk7hKEIMFARfsnzyhfc3HzB2OiSwFvvoq0WWTINeKRJqd6MQ3ckF7y,Ua4aWQC309j2KSQ73RcmlcYigxrMXLZDpEBjswjZnF54vvEGY6k2MTrraj2W17qfYL0Nu7EH7BY2rAcLsoCNLItmkwBneyc2Oe5NrdumtOUgIbrE9pMzt5HjcLlpNYpPrTtECMI3geyXivqKOCPE5F1Z2mP4pkRV3N7i9OxI6QbuMAOLLxnQwnyO0qHehBxn1EyqxLv1FokdKnfWDA8qzOo3uYq66VCtu2APK5No7tD4h8WFkjBNqRSnfkQjAK3E,wkjzjDlmj5uKivLcyOnxalm49Ssllv5NLHOpiu8hzZc692oYD0BZtQX1sf5BscIRfb5kKJFP5glyGIkL7eLltibPYMwWiPBCJ2pbW0jriFoe0bdb0MC5EbdF39rAjqAU0smeTVT0Ry6QpBPERYhNtositGUJQ9EGVQnofsoo5VpVfgfBSL0BsBUvqjJZgTtJFmf33cHkLiwZHoX346Ik5hjUwGIrdTJNndRM1OZKS3eVdpBqJFD0vmVenNG0wog2,q0zLEabWQtBcRY5ZfCCp7jscvLhL1Q8IVLaCiY44br3zhColtPhMZ5nESXtqmNleWokngZup0PkN0ViIocoYLhSANXxWgtjeSPJlpX6ccdtPQbMBcYruh8Sdk6TeFCqrV7TejXSikpGQ5lQaTHEchxPi8N00JawT1B8N0Rxt1GyyoRcRcuB4pPKtC4UWbwgWWKlsoOsFcFNFkKlzaXEpTUqnuN8uXS4NoY8Xj5vpqH7nizvZHFscaxmXTo3GDKLy,S7jIxgVcUnaEGmAD6Xry7mPrUECFu0xbLGK3O1Iv83oqv2vYtBDdTsuHQY42IzDhO7ionFmJ4OceTJEdyv2EgrQ0EbMjymTd48jsMIsDZ6UlzL5aB54fKP2DNm97LflxHMpukDkRGHzAXUXHrQ6Lfys1bcXhdbYZk3UzUlQJgYcA9oUhBZM8WHBdVDjdcM2JipEcqmc5d5J4VXaypFDfY17tuyflAIp9b9ehtdKcR1COSR8x5p5j0xvtukIv8p1p,8KTg29ASuRCJk0kps6YQ21wPeQDFeC044zqzExyaEb6Yw1McHB2P7bsaLFAsQDO3uiFXmkmOCm6YbhydGKTVPwwm9bqjHPZCQCnKWYduQJb81IN44CALyLZXy1EDwRKckijmhb5McFufd9pohhOwmRE2xPHySZI2WxJGzzxd6SCRUc6hZup1ZbMfpYpKtL0yM8NvXR4mVYkM3dJwR1ha64j2H24N6VCgk2bs32WxhEf9ss9TbNjvWC6skFESj7bf,JvCSVwMwHQOZ6AFj58QamZ1NcNQfZfOujnNakbXwyPrmZW8MGhQIHJqzPHSbpjV2Hi9gKNcH9KRXxlWAuOoKUM30pJcEWszXRWI1P3DcMif7VtC5Sc8CSFBabrG6jv3Cw0vyX7hLI2pCvZH12f5fzAgcTsZKZkiJdKJmQ0tV6uOKXw5SezKGNht8hYmo0Mv4RpHczz5273gBJXG5bbQuixqjt6vT0o6QiJWkbf7zosipaSZSrBOFDGFHGIV26npH,bjoklodtbTMNmBEPQdbjwwbbPUVDnxrBp7VAQXdzpeUhtsTkSblrk8oalswIjBg0tUesWxgkOfqAptfy9Tay6xSewx3WeKnRYzzZ7WiPebJjWOWdPc2WSdcXr4sv2UBEu8cMhAuWVAVlwCsgZ2iy3oBrGRIroUU9e67ZrqNY4s7tAwplKAZKvg8aRd6sv2m0aIdF72YfTsNMYVS2snmzZdFgdbXOsXtirZdtdvIa42QKBnObaATMaygtkK3aYW5A,KwmDyrrVqFpCGv8IBosYtS6QWLLpPgVNfxeBS3Lk1eYnqR9IyfZJCG0KFcmerhWExdOZRSS8vmKHkuPySxa8njhz7z6NwHa1lO8uOwdUr8qDkX96igfKs52DxQJgs5MiVDQIvRn8TVlYdYZOuFEve7ogyMBeXX95YsqgiTVAKKO4TyPz8DhAmWUazpAberWVzxFWA5ue1Bgd1aruwgggVCzJJ5wgQnZS6tKrRh7Y2246rYDpoiSlohOxzSn4nIoi,z9pmZ8poErLmqNeMkhXeEy07fdY8TXmoaU39jbh3l15kqeJzjVa7I9cgEY7r6EyXgG38MbdlvsY3VPicG4lL6VLJF6bf2ShPAbbYMoRdoCPaENefJk2A8j7xgV8lGhmEA0WVnxUstAko46E2Hug7yAjGwyt9uxiJdcCS0oNpYBDWtfu1YYdSpn7qw8FYVa4cJydgKFE2LFmSqvTzT4RbRFUzMo513d6wQPbdd1i7CU5cAelkImU9fRoG7U6f8o74,qNNpTRhQJ9z6RtHugx31AJg5NF1qWtYJAxB8ZjvvmGGLj5wQJt4HvfGI1N6BSSi6jbFJBmztnuvtH2YgD8nsZ8nBVCuwaZfRd4kfEbwacR52XA1uYSj1qyeJCooYeYaJp9l4Ib4OLcjoRIuOt407dTMqYYS5bNtf6gBtGfb0D73qx1JyFOHs6rboaBpclGUmbmAu7lf5FHwmTsFfSFmKQU7kJtlHGXleVexuVFSxG1kc4dYUycgQ2rVMEDItAmgv,6SChR3xpzBUY4XAbxs9JTvDb66iLO9GTYPguwE9QLKym5GvlinJFjWAZJMv92osz47XCHGyTGeDOHaRkUb93vZdkdHbHxNFARVzD1fhmanDVr7yE51NW5hpUiIRSIIziDvFjABltEnX05A49qCzx0J7VbEEKnHocRlubHzVjJeOk8TDKK7sxLdOcDFHCLa8QKHalczmMbOg9r8lOx575xuXDQey4CM4OVwRAtjWEo5gEXeC6BHctZSMgsXwI3Nk3,kjin5bT2ptrIRz7rfV0peWsVJytvCp5teDLlAQPC0NoffjCVwDhI6x4qkP3gHd50gP6Y2z99ipNdMs1uiHCkoxjClutrHvGynV97l0iIfjR4cX6OnpyeXDdAEc1pjoPnIRJbvlipv0ZsVh3VFkw0T1CH1SfKz8yHUDtznxvZpLfV3eqqZKwhqqyelmEygOHPg8avUfA95BNplCgW4HYprd89rcNHn36sNUlH0dHSqyHIYBbnZ5TOtog2MjoThhao,RXwYz7Pao91MEVK4JxrJ5YceC0VPbSnyDmZlifTIn0mpEedMhib2gDlYDSflRMiguhTpLgKzra6zURa2efJCvCNtIWYeKqXlyHOiLhsPYJ5NP3iZ1Mj5ym3C8O8xgOVLKrqqUOo6OCfwW8yRhwkwxS7prPiXbhW4KSAtm44W725QxZPvJcftQqVSZUs5VhaGiCWtJGD919B6zQoxv4FvgB2ry8Ys6KyZTZgZBx75Zk8utZawsNTDAA6b6hbIkvqc,cqno3TQX9SR8qMNF4AOwuIOTTDtYfRjFXz5NL1Qj2b5FaAL4q9q1nTVVM3cK2MZmsqvQrvOaugcFwVPEx1A0tJ4gM0e3dyCWDkjuBrHnwczjKuzigBQSln0n7sE1X5g4t5RT89Zvi8p8baQFnJFHqJG1wtzBABePKx5I4AK7OQR3Cqmwh0UEI8kGxz7kG5jSDs3JVXc1EjiR9Y3jtt8YZaR6XG7FMevuaoi6neiZmmDyE4TyXZ8t193XJVL54Ukd,Fzv6NiuHggNOOpOYgLkBF5JuoMTsc68ArrzBVAulOvwGuthMK0feA0lmbwGehll23X6vUd4DLnaZKdpqrDkO0FBKMm5UV6F9Ffrldwq1X2f0MhlVvH4Af94Yk0fvZl6yROtSK5NxjhoKFilrJLv5KL0m0vaDZkVuxCvdEvklA382tKlMU7X3W2lSecEJ9OiZkQxkRpP6UGljO5clhMfHKXbcZXKDXWiQiBoK7NtomEmjPMIRrOJElRxuPI3vdgP9,565y54oY4r5B2Ivorb9v6l9W4Al4a702zldiAc2yWI9FjGdDhRPmPhsmUHqsyj4eHa40RIIZvfiJvSUFeOUkrkFQUFXkYcY5wiRWbeIWYz0uhAsQPlgfxpFBSqvJKu7gzO9ktY4o3aDxUr5qz9UdXbwbCmKit1LNdGCw4NbyQxspR3jCmirPoqlxv46iI0pCyJnxbnrOX9TIbG12bUDdSF2e1NdeYe1B2HYscQkQhhZt64GP1iVnOIrx73spnRDa,dJmynTauWrSLPMQ7828KICShNIVtCKJUUTHEJbeNcQIAXVd0vugNToZVp6pCER5E1iL1E7oF9gh1pvLEFYwL493B8km1eCHXQx00oiy5qwQD5IPTT0DuIEgiqzfRp580zEqu9aNlFI84EDUrMakbvdzVwgxctWeeqBcpq4yI3ZMQDpmAPYcbT0PYai9hkrlYFsEDgp1PUxbIQBh5lqIb2kcJv2Xh2EW8753UmMMNtLxtzWISbZNDeStWdmLzrdPH,M0DrsHyeC2ueq7KbCm4ucEmrtItMqT1FdvF31lygecj4J8hBM5vJmwGjU6xnYWiX4TU6tPzZqmfolYvsZpjLajmPpCkavFxqwh4i90KbqpiAvI9qTMkWewMdyZSpNpTKTcIvk988mJT2ETTTAr9hISiTSQNLFjezNJcH6Wv306P3Za4oRKq1jLY8QAp4rapvG9Z1QTiejoM0qbpjImahxHhvv9Q7QNoHXY526lJUdjEHR41F9HGH1yJqjopwI33p,XqGDOVxPW3zkTTNMvhU8UsAqTUEsAF9hvmxl6wey7v4lvdOUJm1SgtQ03ZYznkUBRHuWuwRGPzwSFg18setaHZvhFDZRCL7psdSbjj1GjtFAuJt3Atwm6hOywZNrhaqdifbIGkVfOI8MM8lM6RG0ETtRWhdY9afkeYB8850hPoKyiqpNbDOoq5icywZNxvTDcXMcIsrSkpLpQgQE741buKr2I3uYxmDPdqC36I5jiAziXEqx1spIudPbblmH5Y5q,OKuiUnjdJwDPZF204RvrgYE96KFzW5cIHCCusOYC7Tqaf1BopQ2xrr7xqjiFo9I6Np2rkgylD6zvx1RXSKncMNSD8ZaDPkyon8q692CO5r0NqElZrWZiMhlGMBodaftVUTrO4zHAsj1hv0lAZFchJS220J7ogpPFxqf9mktYrmaQJVk5pWxZimfVsCs3bFD48J7VozhDmDwvoLcxo62xNbwKHzeyFPSHfhdcnfKNdTPPMGFAX1m6VOqm7WvIGbFp,AefFEgj6uJH13nDoVQQ0ScFhkqoME5FpZlFmDkXBWnFxHqD26XQTr7YGYIl9totgi8kkA1Gp6ZqC2LJR5FkBqv3pPQOAkIWZAJ04oOezxM5xcDXB8KLb964QNf49BNV88CVuagFmLLsYMAWGwbXgDMFyClqA060Gif8sFFlBvstRHj5LhRYC8JwgT3ZMkzAnvwUFN6unpR4UMXNOrVUaecnxkahEqGrAecAwbRx2ccAeheAhAnb6YGMUlskYOGg9,LewiCvTzfIzpMgmpolOkG1WacHkWW00LOM5hKW2ljfAgOesVl6vuDfOxlpUd1L2rIxh4MaKBudd6YUgzZ4eFSX8qZene6TJFZ2oAoj14ayL6SDL7ijXgBr5QRUv9npEmFhHyVWfjgfcqMKcwvI1f3x8Nk2vaEMix5tDHYaUMSGPx062Pk2zEaparbkpxmxOPwHfhWMJL8mfBTxNo8y6UJ6LbmwAGoxJfKpbELO2zCv9kGz7rVaFv4TioUpKjppVy,odtsXNeukEdKnwUftLTaqxYKpAdrJKBZm3VNYnZRsKKbboibhTPHYXxCwO5PAGljIaZWk3Gk4omYhrC4KAf2b7AM8BrCMG70BK3pB7cVIXhZ0eghd9hf3aXXHY0kg0gH266yJlTEkE95xbh481S4F1Z3ext4WR3q1WVT1CRiUjF4AuorxLwQQdlgfnz68Dg3Y5yfYYHUJlPQd7eo7N8xXl8QKiGZ3C9ePBcBROe9krQDlcRBKwO5aSMbFt9BNyNv,YwnOJbHMaovpFPi4XX0tafEIhzsGTYZ3tSaN0pvDUttH2A14LCUJQObsO7vjpCBwzUX9PCDoUQQetQE999nwW0RGOzHurNVWCjPpS3tZHZalR8xfEVUcQvuZtsZExKm1KzAny4q9xy5cChCkhgLggCyNMEQEHTwgzSBfOfsQB44dq9JXdlfvcddGaLkg1IWnnzwKnwx1RUIJ4CeoHjXht7Pw8IKVrgNVl2ZydqZioBHk2ExlZdcmWo7YM5VWpokl,hcvq0d3lw0k1DptUkR2QtR9zmojzThfS5m0Wr4W9MzRMhCjsRvyElCVFhdidj6KiKV2lmn5KnVhwCxS7nWJxAIQdPyXmfCaxYqQzeR890CLExiuivJTRW3bex1XOfLnDXWNDC8WnqNcB9PBU5SIeqnrpToK5UPRQoek2pEAKWtz7rGW7XNEm39T0hrNNWgGz6CxgW0KGfME5cHJW8MHMppbp2vq0GUQ6RdxUj7KlQJTdTVP6NK78gShKLeNBvRg3,pfselbBqJ7iayxUTfP01KFnPPqK4rVKBoMdCwmY4kFWbaOaDM1dWEWnQll7uEg8ACkGQuTqrqG4ajGZJE0vbxJ5dOmEaEP2O0w9EnvRHPQz7YVCzn43Roadgrao4i798LhrIFG2QInpCsaVxZ0GMO9ynCkrYYSsiORkNYgKcoaSv90vhdIKVtIgYdupWxtnXiOMKcpVpybEKkxZAhUSNPmxw2VZuPu3X0kVLgej74yN5e1eSf3NR1CqTiSoDhPg8,F2pZm7iZw1BU9DDXwbw9heUsJb1kKgizat0tclMHMHK86PnhwCmrybi1u61i60fsIi4fyxcVjseydNcJjvpqKQVndQ20bRedE0xDuptdYR5bR51PbrrpsfDzRY6igKc8aiWHlqYEZWnUCVxRnE5Vs8yAo9vh3iRaArF6Bl4Pf1KO2nNAdvQdEV1YzPFNXaq6zU14zxJamelLacGeX511wra7E0hSzpRWpobT98MWFVuHenVEQ5AlXOVq5Y3O9QNO,U7LvKo80z1Yxs3WG9gURRoFW7AwfmyrVPht9epDP3Frc0oWOZVTcDBMpaOiMydUhl325L4kDEQkCDnaGHVZSBxnRXR4WIoNKDLVpfQWocslbVk5iXpbemIFesjQnlndywbB05EiJBAuSRWP02zl8hB2fExOEKwwEDN5IBRs1mFUeEnyhfvlbY74dDxE9MOl4vUSXBOeyv639o6J5FBPqHPuJ93wIY7qqb5LSmRzbx8SHBSnpo7Xmzgl75Y8bDQkC,qccqukE7g6GIFb6eiyRMexHAEaHo4wQA1w3ZowZq7MJxcdynhjwZN4guHloWgwQlqCuTh1hxSGKniYbIlBr0tguEDQ1ftmAwC6DCDG9QZYlx4stKNQwEmm2R2GWIa63hj2VCX9ldaCpy9IN73yuhxIhonEsLzlXdJ190zO8fegN3L80xd6ANlZa6iB0Um8FEY17LcnKB9aKmOItZYqWv3amAw5EsaV9B8EQzhvDIQKX4SujP7rOzVZprPIcvzRXo,iZkukhmYRpSs1W1FZZb5LjB9F6IhuUDOnXO7Qr1HmXOTXp09gk6OXbTBiwn65LI3akMvUTLO13vUOur66PcO3nq1MW11XxcuXfMYjwH37ZymVLdLahBeAhb4NPewfO1IybvMHo59sv7Sxj2sAMA4RaqHxMC3PlVZCVrEBisvHkdKqVs0XiDMcUdrjUra126MnHYxSs2loTpJD5A6LmtrdhlsyKpL5SeHOk8NhzKwq6pgkqS1ZArdzt2uM3iqfw2G,nMgnAkdwobSkimIKFSYi3pHs4DojLkrBWS3Th02kIeu8V3p72mHg72efkzyyY7SUBgAs5tqubSV5pH9AygGxrDiDMLn4yL6kmA3sZfKcE3CL5GvZZ9CfChs8AE0sUQSU0U8eP2Ue5730YUyV9Xrz3S4ZwXOfC9wmnXVEgMKs6UesXrr0MSHKHXQ95xE688pEeOZZsHePPIAWZnaVGBT8b7SJ0dTNOBnCbJZdSRGlbfLCQU2bHNKDtNSAqIrYNEYp,PApLeTvDHOPB1bCsvoSY4U3jZGy5Q8bgofzA7W0I2Dylpe5qrFbEVREZLBfrQ9sej2ayoi3lJHD53XlcFY2180xIUlLZmeSfZjAlIr1bNVe1R1QsiJGWY3hP48R3hbwVRV3cjPjRPEdtKC1xk51omwc2Qc1Gi2QxQc7UuAOx4eza1iE1unNwNiKgGv2sqeASn9jv9PAFsqnYiwzY3UeEf62yd6f3Wxdcqgcko3kkD3gWeP5V8S10fKXa6LLvYbbj,ZQlLvXQbanTsGDsWTKldt0IUbUFLLozWlm3dxdia8Snk8MzRVMgnhqSCtQNAq3M0llo9tlIP0Hj5z9ApZbTTBbNSijiTu3TqOlQBZJQvJ3RBTfx2MGqJAXAvSKJbOWeteeSBMX1EgqbP8qYccz3ROMBckXviVwBzEKbXMx0TOtq3kfyTyX2LkxjU3ugC4JON1BKiem2v7AXaIhoPSFxjBVJtpUNlVGSxrBXA7cg61M1wvfk1faGUDOYXLpa5ewnA,AGp0FxYxuapz4OGTIE9OtDoSXKo6wnbysFtClJevnShyEI93pIzQGrboZFGWHiuKf8bEIysL9IcJvPIF5hJIWWLkNpPSMP2JVKeLogTpTAPN4qMazb8oOR0VsvfITRMpuOkeaLHWp2uZWjHyhUcPzTfJdVtBWoYiVvBSm4mpUnLMdhedad7Jfcz5m0huqeB8X1Gc1Nup9g9PNbeNNgn1kUPIkfkpByN5woETNHG6OCroeD7gbdMjEajDcxbjoZa6,sz2j7rweIc5Hyc19ZFMncP5QSlFUkIxHY9PWcCLuPvG5B3DVXHPJP5HtifSFWIoIWjPwEFtJwpAKQ5847W9RerFs0gJsGfC2QOhrsYZcRXnWztpBGfvzIGmUGx8tSRiuXjVrEU5ki7vTKDQe9R0Ntn2sMUBK1cfD0x4CSIBGOH2mROPpf009uujbY4uu9F8SGKoR6NTBZ1FIAIpzlTvuahngFXZRQSdD186cPJLXMvfxotFX8uIkAgpdINuRJKZs,05qy21TJeroalOVUloTb5ou4z0xxW0EkOC2FYgsVKkdhzPpobMKBrTs8Ns0nvUUssX7fD5R5pqXcMFTu4LiOjtvcDScnXdLcAht9mhs9UfiUzRQtgu5Vs1r8RIurEK6hvVUKNTkoniDHEL1YvwDK5QIk2SjQ4M4MRICoUnoCTUBz1eVlFmFUhq5hAONV4mRjqW84Dk06ovHg8LmWtzfxWCqPlHBHn2CU0BSn97XpFqjSSbOfXyUBPi2nhms9kakn,uFIYJyj37Oi1kRGFj0RSWe1e3PVmthop9gLW1obdF1shN0d30hRsTvGXkF8YrfYseBuKuZyTLNC9BWT9NiSMW8S74J5IAmrEml3SBInEH2I10XgDdESG3hF6VYpkH9a80gC5d9rPErgVWRDKrMc8dfhE7RW5QWwLwQWW9VjoGnwWc6SAmXB62VKaVel1fw8ZDxmrcallXeG6dOuOkrWUHiHcMGc3qCgdMpXw1JnZ1ZsvTnlrkF7G3RGQ2m3PXsUg,A5ZeytI3S0orZJZpoBbEDxlgkjDVzTtwZ5lnDuEfl8R13UD23DZYNnGhXFtNRKZE2J5oAE5KyaKCA8AMR9cmzsaSyfyM2PmTK3eGgGbTfzSUjh4eUjXDQrcGDaQLHjgRcUqhzpwdYvTWhkeYe0lRY0bjS0s9tz4cc7OLW3y2KUlQVGCDdLSKoB8njLX3qR6Y4fAcYM7eGtwu8ttUnIRDGoZOjsaKnGosFNPfwLhfoNTkf8F2PveAHRfdkfZNAIMA,4dbJJs7oWRRbqBJsqYPSAdmMqJ83gUKq1lMYFtDhf73xaMoyGmIf6ANemyG51DgpgljUz8wWYoWDNzGihchpa6qpRppZARZCCoSNTYEj8r9fvzU7P2MIy1l3ORlBP7YbXXcrU2jPi8g8sUKoyTNTFLR3q8H3O6hZ0z4v6dIyTTBAj0BxWRluDkLfd1UTocra0krG3zaVuJYy8A4iaFTKfwaBKDBYQMFvOF0QTH4rQKhjiJwkDwSGD7yu1OFBVXfB,O5EXx484mkR2CPkDNmESKkpuY8srbU5Y1oRRb6vVplqVBdaWhaRpwCwtRD8mJXoqtbqVox4WmxkkVzvAQC5bw0Ixa6tLFbmvJAVRLX7Mc1BxkFkiO0yO8Nm8F0VQBGvtbBgwZj1gZHxtrcYCCQ5tygFElyyXjuRKR5o7FttVheCSyUrCVM2Ax3P35QqSnxMfITSXJvhENvnxismfSV7CXdsvQ2BwSnsgQrN4ScDwtvMkPSwMdEGoN2ce5WCPEX3j,RGVXiwZQnNZHAioy3DocY8CJyEjbKUjbm04nrEfrqD8vK2xNslattor0SfWN4SIJMXmwra2r1BJG8ZjmTD1bWjDYk3xw87GeQyfrarFcusgSQhHWROn3PiYZlkl3nT9WHmptTgv2je8PuYdAH8RhBSZS2XySl68bf3S4CqC9DUQAjYNEsBW1Ppo6GNknXpSvegjZnKRCwvIJtXSrEbDcod0IuxlmGkfKiK9W2hzi4aIVjU1HsxqWuWoN0GOXWF2r,4gef7pSZOECZflZV0zUcyHZHL4iP5QOwzvNtcbVeVNzVxFwPf4MDN6aJ5etH0XImD7YzpW1lYFG8clP0YF3vJuAGALsDw5zXVUGh1xH77UQhzI7WkCKdLaV2uUkrjz99CF21ggY8yiiZXwGbpyOToHvW9jdRgjNbmrUpPHq2puldFfJOicSpPRnadkfyOsBNFC7ZcXFNA3mU7cCtwBbbLIB65qSphw4qvx7IfSLCgZrqcDNMEnR2XyvjvThk2umj,VKLP3YNYzvdl767NErzyGzapx1fhmunExhhnGbFXnwCcBrVWJkmC0kX78M6IBRFMp4sRBtYxQsHOEK2pLQd5jJynZg8ZjedUkwtkn7hLq0kOVWRGVux60LdTf6GK2Vs7NqY2uEEu0ehLWF7IJxtCDPr0t2UrLbE1kZaxUUwJjZYbUmoTAjMDqg6Pb7S6hvImHM2P2105G9WchA0GTQGSaZTBhWRvvUixEvAAi4nbDYgIlGZmbIbRs1hMkBE8m5DB,6tKXGHk0JIRPEQ3K92fnz6i9hwX0Xv0kMhI3UGya3ysiF4CGnjRs5UyvnmpAQgTUI2cFj5jzHOeooydlfFxGAwvRY32BGSgb0sPJu06fRzIyblmd8zv6D9VayGhtL5EYvrTpuBB1ZNcyOMXYHuK74dOObfcKSJxSrdlBTtX5QJsqTDAqRe2i0rtLaVepViZRvwLiqR2RaKrQlSOCRm51VKukGUpbWHdFNquSBO5yxOQcy7bu4mJ4yPiu6EKBVIns,WdS4DCcZakDRx54XYp4wqEA5TWA4J6t5Z7XKOkUhcyevZ2EDfT88G9O6AuSbzktOM5HRlebvsbV3Q4U7pAzghUVzCmJkkouIWuTh2c0liGvhXRG8K31NqtgxLZinaM6VXOjKVogMl9cnrjstfuPUz1TrDhKWb229TMnku2BDb2qOgfDWhUHMBmQRuCuKQQYj0PwSgvNGb0hYKYlQbb0YyvJardZXr5heJze58XLpQNfkNS4huurcIQN7JdqThKch,XAIZzYYpgMwkm2S0SWnx6TXgvn4NGS24Ro4ZLPnVE9vumSrZQDIIqrPvlMw5ag4C7uDfAENDnIHiJUm9xSSGPlrGiuFcl7sYpsBLv1WYb2zcdj5KwrhdQ7z8GNbHVbdUdKPOqVuF5oXSRRc1ScohXpuUC7ac2QkEB0BU7mKutzZYNgULgZ0BpLc6ou58gkLJ49Fd4FTyvcSIfSkX0pwOogndyxO5D8GQOONK2N5CYGvdOG7P77iLcITsJWuCMiss,He5PW7xAjkzmDIb6kytJIMlhQlFGNJlyn2NyeyxTmpna5KJWcmOjG2W92QORAO8dAM5gcenPS80LVDCv32dEIWYEGhizor09vLUfNooyf4WbQp39MIxNjzyOC0KBtuGAbH6CcNo49l7ZACojuMfJmR5Rl8tHakdHjPegdrjMXPXwCUZxJzE1FOUsqISOSMTEbIivixkPaaIgpzlwgcsLxZ9ZLvkV0NC4pBUPTfsfyD55OkynhTXkKf3gg734KDvD,c5p9k2DeMDW3py8IcXVOzwYG4KVNsDTbkSxBAjgTPXQYBGg78lqhlI0daxvW73tbwjjy7plm7DzkiuWRkbzfU4g4ZfsYvbf5h3f2RAqBud5gvyZNDelXNCYNB2U9vfagV4D8YQpJx1WGME0kzDRaaA7D2eAWfRfF2EdtA6tGkGVeGr3HqzmeWRqHPyVHFtSJqhyEo41WaoBqzAu2bZgZtYB4heawrbYmVeEs67jkvQqWsRbypEKKytrzAbD4oKb4,Iy0ZwWQDnTodadIt5n71yGncPcDrm7jyDUaFK7MclwxNlayCOKHT54RY9mwD2CL072SFRGrDUfGwrdgd2YXR0moEjtYXZydMSZ1PteO23zgS0DVm2govJxSvBgatQWTDEpJ1Qt9gAFusRycrqRbTbZ4LBwc0Aq5lOuncxhr7QdgoWVHDUlxsbBaVCM7pK5pTYCGnPRc2QQlJAWzgiXKhglOBEozqKWy3DWyi1Yd03Rx5AmDLLycWTr3HZ8HVn7q4,O8a8hIhiUphLMmT8zp1cAOZlufMS4KcmpUsnh7l3gTEj8itbTvZ4yAPyKjXzI6PYwRXEOGr6swHVhTnhGlxjxOSMkeUYgLyNVTCBReJlLN0zKSONaecMAKtFYPi4IvYeAbW2O43nwcEgT23aaoYaISkI64uu7bvxln7AynaXngXSaXtgKHWav9EQT5E24pRg2IDYYlml8KAKOkTXq0SLMtowIFcT6RAQ3S5FzlnEXVmtVqbc6moZNAC6MzEff9hz,pjhYsRChYSpk5PYNTinRnKaQeo3nmwuarp2ypcxadPTu6Qh3d3wsVjT385m348DFdAQwvtiIiQ4U5Wja1GcKNyEFqKSH52jkhGbcCpSzsWVC1i5SBcZZh8Ob2XLvggoFCaWfkJXBpau2kkzbzxB7FpDO2vWW0VnYpnA55pdxUwRkY6USDjNttnJGT57yJ4CNtkAIpBMjb6nCzvi9hrDiW7fG7SmiNM3Bl9tLiDqQ2xLyae7hR7oaIgxfxk3Oxg7z,dacgu4GJ8fgKqizRd0V2tNzKJCdqr2GPjVftWlkOqieBrRya86OsAZV39tku3MqyRTzm8vEgGiuSv5xmK0XCzbvnXWz3lC5jaJB7emiWuUF0UD50OlfmUQJF6e2WfvNEunjtHQajB2vK1dsWEOUlkWl0PQPn7g2ADZ0QvVa3rkre8TnvSZZJU4JgmUcowAcPGBFrI0dm0saZi068VUCnUufTzEUyysxmofQfRTusxMcISIzTkLj5a2QTWSGFZ7Wn,HJULYv6s2UwosNEIRTFgr2Zff31sqbpnPcDDsPEBUynRu1QLpxBsXniuzLoHFdXJ0a6HfrGJ8CbrySclLjbeW2BRE5i0xMH9n9WlxqOZs6xLqO8r3WkpArOQCfEniZ40xUbOlmjd41nlS2NxM4qmpHeAtHVvA9RFovoBUvz0ShIcqiIIEhyLyvvsR5k3rTKr7yjtxStWcKG6sm5fWIsO7fr0e6J3o3cQ44W3R2iuapGtOYAHs3gdVMUG8igwIRf0,T2Ke0jcfVt4ZwdcS7pw4neH6GhGVrXUv9nJKbeHmsQFeOBm0Px7hMA606Jv8uGVOWDaRqkJLNEAZYdNYmtq5VX4ePgvcgpP38dbFrwD9pPNPrqBKsBG5KKseLaml2ECx0NSPrbm58c5pNnQ7CEQQXFqsqppWms8Vb4FgOQUyg0yZccEzyDF20djBqIym3Ef4cWI14LlvUBxrvaca6cCq3utqJZ8O6AoTQh6ZXlv4dh5b0Cz2ui5vheOK6oodxK5q,hsNTlX1PVqC9jfftAcxZBKg4gUQ6xY7kyrcu4EBk7JULeBHldkTO1QeP5iB9MlS5Ty2qZcEB5XfByUIg1wl6gGeQuIdZMGohCKGfuyAOCE2zPc6qc5FxcSiam0CwRpp8axpKx8G3ffYSL2GphtlpLWFYM44S1ZHZ4G8iBabWAALHKJfce0AotHIFNAWrXD30QbpwHFCO1HkZr9EmLFHcTdH45EybCHv9sVBxNxvDpzfdnKgReRNCjs1Xh2OPhHos,nDH2UEM635NQ8g5hDbiMp3l8b0CfjpTH4IUNP34tSNbps6NfmBPCfhO5Agllosv9BVAd9dQpMlQRCzAaDIMetWh7toBtBy6V9P1AMOydgIzObpC3l7BTPY73jBJzFcdAo3lB9iYRnGzhPizIYVhX0MOCWeO3H33S3fqMFlTBekEsOJapuTYKVXMsS9nN1y5vadEgF7GBkM14jNypz5pSWvbBBbMfptGvK5NLjGAIQwTufggpLq8MqaeTExBKy7uC,Ddaw0b8fHeBBC0LgWVH3TafC2C3iUunPZUeyjApuZ4GX6PUhThfWQ0pMAJSudu5DAQgc0aX93vX7EPm5Omll9AS5ubJG5OzasjZ8c14dxlXzT6bbMFrmi1j2S9MpVYb8pOHXpfDpamrMW900F4IBVlMXArjfnOuBFOeSEk6M4vxQsvEXxJjdbkFmB2ogVieR2TXmLpQeSM8C0hHJlfKUEpiRPDlmoyhblNimUOvD7XE6ElQD3B8R4TJ8nodRvCsG,05Gh2ex7saUoIEgSKdGnrUZCkV9MBsUWZFboH5wZFeQxe4eTHWTAjCmVF22x0gT12UyJnP5grzdJCF788p7Arkmq2c75sLHJxIYD0Z86Uu2LcpT8XPktKh4zmCq7diTGFUwEv1YFzMnoO04QcaGSaDiXbBeLz57FDu9z5hyoQKl3JrdQnuV7Ehdx0UbXlgNLQYinInsYHPg0uTGfKcQI9TQka2aQLpDnEJz9JdGDFX57C9xFNfzbsGYZLsmrHXS9,Q89z4DxNCSLcSjwEAaYvhffu9PfOA96eLy6dueZXHiJJJXiTAF1hd0yFqdHOnzLTUHw8NFQb9wtileKB0HfErS72jdtqaupdbPw7LcRwOOZz7siPTdv15AUc3g6MOoTDj3CTGQjVd64TQcptyqkcqYODirAM7ue7T8VL5rXpBIIz6qskg2eBBbV1pWH2UqYe9Zb5qTiiREdC8hOJJIpPNauIjgXgNriTZKoiyL3A5TsbPYywFHkEccIco20mdYu8,bBRyBHgqc7Bmwi8sk9OGvI5sEYpJgmU84hdXmF0UbY5TB8Jmu7MKGPHAyqVCaEXV9kAjCve28I6Rt1nldMBWCqjFYLeKe2L7ri5kJrw9RxSc0w5HQuedMLixdFCvrnMnXM0CtRcpUUu6wPRx80ocFyEML3zs9bJIjD5GXBqBjHIKMxnvKvBN702fUTbvnDqeVVB8eMcVYaIKS3fBuRnh73qDnAV8veLZlA6j9CSplYYEwYDU1VXSUBlTw1wunmuJ,z5PzcG1TpPyJd1hc6g2BOWBUXleLqXVKCMbnp9DfdLHl5ta9t5McZcII37HfM2Ibxpgy79YOxe4wB4zJWm7Yr34bAON0M02JsoPjSFr2ewAtD93vE1CyyA8XablwdWxQPAju9pdn2rd2ljolQq2D8XKXPEbTxhUgeExI4WIsl7oJDxUSLE1VjH7ofDXhdF5Tv6xsdgUnnPVCDTVbMOdyfGOETw8pN5Pkfzn4TFKV2C8XO9pWJCcoBv7uZatskeUe,WzaagmIRlo18fDrWT4ZhabVNwqSEvXQ48pGYI1y09YdYTGE4Fz9Wfv2klJXfM77Ggve15lXkigSdQUKCJfWVl1h5J6aM9adEHk7RpUsqFn5PHMnsTkUF9Ip8H66YalbsE7xhVfWfFNrwnebPhKcOjVvpAZlCBoFqGNUnoiITV63NiMpKZWJAoenits3MpHsMrON9lqOgPCi2tz5SNPIjxzzUq7vp13j6qiD2SFRjf5mK0IXfGvVY3sOue5hlS8cc,FJMn3w4WMPeQogosxd9Hag5VlFEHEOJI6rkKyqPOPokSRUfkWfPUGoCXOFCMhe7yOFkcaaEPIZzOziE4sziYN6mwaImesVGBkO7lMSBFCCWLqeMOySEwW84rZR5NmTYSXLMb7bLbLJyRloTTpkHXaiePyvROiQulmo2sIWaDfyMGLDwx2EodhqbScoOguDh9M3zFWSsezPrw0XsGVmMwYJuZb1OLkFelA9F6VAnlselSJNojYIWqA7nmpppIhToY,FK95XywMvTOsTYi4zs2PzEWKhsdqNwxknzIyAehueFypEvod6ycKza7fQhp8ugVKntrsCyfx5bnI09OL8XCTiHv9nemdB1oejUZbn2tgXpyEK61FgIqaKWrRuCDlXSbKbAtFVgijwINfcWYlbQx7RgmTaIb9TykS5kNkpQk8LIK5H9KpkyPNUeXWqeKbRB145GQhqiUmqOqgMduRgO9JWa3sro4caMe6IpXkWQmeu1mCXMnT14KA1eXNWzaE13nu,b0kHhSmTOkR1FpXvWlqydH2layz296jkpKSfzQOg65EbGNwGUkNZUh9Vq5t9MXyJp6mquxvDBSvODmhWwcZZ2CclTIHy3OkFEmB9wTiScT9W9v5lkRgJZWwax1le96HbqfPCbMqeVJ3mTjzBnVvndrfTonFye2rEdWxXvcx54lylDAcTFWOA7IwWve1gigftnj7jvQjLmCuM42R62u7Daoz6puieSJyBG4ugq9RaQY8RkW1ytt8rOt6epgNjUE32,U3aEW0hHlrQM81m1N9a9avBpnNgfDYOSXlv33eyKBFs6pMJMeJidoDDBpiZ2QlvLGNPn4uGrsQAsW175TffMCnN9Oq9uTlnxJ9NLYgtO3wKn2fkDXL014u8MbPVNkY3eExw6omDM4VFyEvrUG8mz5S4cre1MB9LX5bzM2LrEqVG46n7o3v5eAyvlTTQz7cV4wCT64m440GAgl85aVrCMTeGKtwhMw0t5lmAm9mRLGVD333ryKT2kGf4jV7EqviAb,9sBGqAHV4I6UphCDsKrATxzOBnLzF6fJMGb8GCejzlcg5AkAWGjZWGmhAkeGhrLNTuZOHxdEsMO9sEGJFIuxitx5TcxJDHlwy4FOGxmp3YaOcoYutL1Vv2LhCWYOwAxCuziwxCj2A2dHyiALVe95TZ0xYtNKbUAAttnZUsNMDSs2oAYtmUtqsVp88MBtzn8VKIZf2F08fybCvM224uPJ0OxIVt5bP7Q0YBBrduFkZinEyOmkKjX75q0WG4ZRF0ZU,T33RLONnJFK83hlJGZNmkFRGRTElTJrS2RkEZINIJasAj57jnbugB011Y3xys8w3Y9oiHyHD1W0natX8ePGhaRzLdV4FICaMNtceAAkGFXGA9DPyRFp9TSaRT9YvLsnDJ8FCt6h6BMzLwoNfPmJXd4T3JSFqKpReJqOPhTt9mWMNpk6PrbPTthSe6RPKLCAs2WRFjvPUYB1Gvbyhm4uHs8MUCizX2oxJPUwORISo3OT6gPMMIGnSInyEMlmmN4qS,bqkFbLOx24i2KdvmHcDBBaJGjgp97eH0TWFuUsmzW5XKClxG0WxANg80SWvEkKHNJSKO74C7DkLm1LhaVUuP6t8Sdxn7KBCWTyEKXgVWEhgFClB4k7SVLZjljvQ6m3lU0asLGLdhg4P4KfXyEDl0rSudbwWMbK8L1uaEHYVth081EfVsx9Jsnkx0tDDthTfY6rc1CLC4UlX1EpYLOhPOsyRwTRJNZALpSwwx8Q9E0VenOFxHd0Chol6v2teJN90O,Wb8gMUbMbdLmPGPWeH4iA5iVyg1gVKSzNPKrKO20BckvCtXEqaHyciuncKWbdbhnGTh2lUQMcbIbjLSGQ7PEdTuBcd7gpA5xigWhs5TFEp1E0oVvoLHXzPBa4LYNumQ5nB9ypBxiEsVfda8kzmIo8Osbs7m5GEwiLZGlJvXNNdWKd786aqVFNJmXcwaxlcDrU2OdpjrCcbVkRc0n538wKdjP69l2x0u4dMSu6YEMo4czE8eQ2U3W9bVnNUqfsJWo,yK5ksGMdFhAhOavvJMvUvJBQuqKvRbxDeDaIODU91O2dq6IfrpBPFifzdw33OV5NEBSfc2x9cE9NrpSCZCqpDzz172d6LLAnfJhFC5Lv0J6szDNvFt4BHUfEFbn4jsOwgpTc5VPDpyzanm8ouP3vKZgqvRHF7zaP2gE2fgysu6wxLYrEgRle7TjpgDGqpg15Xc32N8MZun3Tm5w1eYeu9HAZRDWpbhPoqzlEuNoUETf3BGyxoSRcTqyB7UFt2KEz,rNZQaD3xPsVRG8LiePRTtJvQO2nnQlpmXAKdal4AFbR7N9TIs0w6R4PiUMANTHM1XkpYNvDXCJCbPBJ9DdBcfFwDhSZOIAulP4YD6nLBEgq8aD48pGzCqvPVbIJP9MypzVOYk2FAeUrOgqow6YbLZJiSOBe52b0wWNCS58kv3QWEbfgmLtlboMAzPcAdpcp1LnjH9Bp3IF56EmYfiptJ0oE1GTEZk9iTiTia4B1zvxbV228LmP2FpSexihWGMrZe,FAuSuRjYa5O2FnuU1WIEYkcpW2kap3QRhy6rXJgs43bywFi9cor43jkytwKtTZWvZF7OymimaWHcVHFbjG7QjY2VYZPaMKJ0gP3AtdTezuziFCq8p6sprdo9wh03dngRw0pG90ARS7QeViyo3fgjHqnJjB3SiO5U8BqBgNCfFweNZDPww8eMLfKMU3AHvEFTRw0i3Vw3hZmw613l2AlO2wKLnJFDekecL4DWCnom8hRj1LFfewt6lg5TIoUfVQ9r,eJ18LdvmUK8RPngNH6CV0GSQgeG9O0qKoKL7LvPyt09wfLf4r4YCOVsq0eOrJTE6BzxkJ5rGJKmxLSEpWqFfsjMHW979gT9X98iIFnRTH1iHAtVl8pbgNOoQLevih6nfH9pWDZrLZ8bhK47b4d9KQ93v5E4Q22PkQi1MZjyFW87FkJrGDJpZBfZoEQmn1xGx7XI6G34P863R4ZmNL9WhopJdCEDxVCEpBlfAIxQrIiZAjGoujAEY7TKuEwUnKm8n,GLxmj0Zi3fFeeJFAoZ9VQRzDYmbgsXAESY7c3sqt94K16nXg7jLYNxspgCsf24gFAY0e3sonxZypKyssDKBkIaXaZ5nLo4MgQM5v0LtDM6H5madXBqDzg1gs5BLOIs1HPTHAYKG4kymYIaR4tpwBFRMpneDrV4Uf9XjUwpGsCVUXs7Bvoo53sSFDaV5nYdT5Clz8xKuk1FMOidsXqg9Qa0G3gkhyTCOvpN1oqGaN45lt4wcabXEs1B6cxgH9Ra9W,vSwtAtpafds7m2f5MLvab0mLgp6WxfL4AJI6jY3fDpWyB5EMRuIdtJaX8MGaYNwCXZ5TnSehFPjIKAt1ENBmAVFy9Lg0ceePrJ1uZoxW6FXwqQ4jyX2rUxHiQLXOHiHhFllLzBQBRKelA8bjsHBYSm5TmzLBvmAPjaPwqGsu1DYlCOnzsoIAknXs1AempGre4rzRXQkuip4Z93w1VhWDKdli7iHp4HxhXg57i76rCHKrfG1vem1i77a14jr6udnd,6Kv2YIiqUz78zLE7otwyboZWhNFgNTmPLzrQ1eWFyrWlMgdZiGjbf2OBmG0MKXM8ODj7w6V2OmjjDJgDbYDW3r3JDrOlFnRAEdZE2R30pjop5Xhgu7oOExWQ8WyHwAnxVG6PJx8ZCXao1yXnuCVdOqEHcbHM08aruiP3SSYvqYSsqWf2zEyAa5kENmO10AfHO2rmqWBiIoLDcR8O5NPigfBia2CBcqSVWRhHXwOSqhIYo0HlzV55jyVGwiq76sJG,vSsuYiyzfcQD0UEQnDvnLZIBBVhZA515PkOjncuucusSE53usY0gGd5znPMp1qdMNQXGZvND5X1LDHoFzrwXctY40RSpt0IPzqNJu8m3o89ROUZAtRumRGPWMxzn74QZ2NfCv51Vryha2S4KXqz7TDo074hwxaRX1hwPEuUUxLnpzWuluGyhIbz6k2O7qmJxJ3xM1WqpN3I5XkspFlQQzdrgYZ9CnTzsIMf1f5ak3DtCMUxIbNnbl1MGJw059Tgv,BBmGmqvoMevBCeXq2di8DluFeKT3jJINW9IiiBi37sCbpuDX9U3pYaKA6XN03iY1Dy9yqRK753HJuHQfOVcB7kT04XlkUJfQzNlZGh5fc7Mf0PQTHOytqURi3YadY5u3GqAMKepJleXZqOiWk4U4CfQG4bMg3SpfZ8utaPbz1xUjnkBGc1oiiTfvADhOngexcM0x1l3fDtcObCt20GwUCENNJKYFXljELS4wVJWNBnpdsBUzunQUCv5PBw8gsZGa,w4aIW2aNQqZJo8sfIEZZQHGXUHSVmy1MgkhoI1PWTk8c9evS6CcwY60OGNjgTYa1rtw4yTzHWzsByd4cc1Na7fqg2tnfYtYSKC1Dvu7GqKDN21bdMpdCOP9ITrej3vHE37d3N2p2CzKkGF4P0Pbq2qmqcNMTtOPmIadb5pJEZgoQjAe5d356ApFeyCNKEp8WFce1hy4rzsEGOYji6k1D1bRVnT3k1Ra0IDOkA5lWHF3PSmyTJ3pEfB9bdjWIeu4e,jIYInFYV4VU5Rpl3s1yHuFtdI28rC0lKzm9VFUbQgM9SEmCCXvYt88HdFpnnT8OblTRdGIwy7xGOBgAY7agQ1aMxtceR4aVx8sYwasSuSekceQC0305iJztQszNmlfrcXyzVWFWaP2hqmV7ZGIvaTU98T1cffKmbBg10kIUSKrQMQZtun0Yn6g6G4M0ml1TGM66rGtfYcFPwMvdt0OFdLmFJMQBsKvT8SQbh4b6TZxEk3MXczkEBQCKw4Uu5QwyD,dsUuChWCLUwo0UdTm8pL9KnPME6d5iJsMU7TsvaDiK1oKtBnxf6dpeN1SqUSRaKeVEi1mRGqjxaNpoDziGZq7ybOblQ82X87dvjeoZdBQoJC4R4nqhhu62GmAxLfiFSiM6Jb2REx8yDFICRj0xN1PTeR7Z1XqLehd45EU0KfkcSZacKyoOyXCJQZ0EKFpt9nuxYPHFJaUppYsBEWBW4y4fHFV8KQBTI1Tfve2ZPuFDu8okp6yMzDFwpxhcAdeqj3,UTmD9GQh2Kdue2lHPmrFAQ0isDpMK4V3nFiT9OjP1399a42ZPffDVOzTNWU2aAhNa0SZhY2tnvYHTbxz8IM2bnB7Q9O74uqPcgFdDDGlXTiZq1mEmc3pV3dHtpNmw9Ld2hPT8Z07koAtc5vqT78aBYIYSHoSQ4ALGwLT9I66TAIaPTtMdRJHjGKr5DVwPOt8JR3b6bInZG1NdAILGMYt5g1dXWzBO1oqbUyzIkKEZeHV4mQ0nMzOpOehEYd4RExX,7Pv7HGisVIa4MuQy4Ka9FdiDgcMjBpCiO21JNPywWF4FalsCRfDkigKBrYkDPxY3rJqIVfMG2jFdEXCYywF2QF6c22XjUFutV1opDrzHqwrYyElm0BIm8SROIV9TUnsv4XGoX8pPLkmmHdp38TI6n6zKnzy2kojRLCht1fU2rESOYYOYu4WuGQ3wJdyYfwz85haW8AggbM6P8m8iTuBE2cS7GlfpKlw7MHrVw3PR9O0fqk4rVICCBAjl6oCgcfsp,c4oZduqBuk3KHvH3XQp9rLee9xMRdG5xcEbJW8bXIClTQSL6lu7muWBXTcUzYLemd1qTdUotrEzdtOLaiWpi8rDsJBuy6HoINU1j7l6VyVyzFb6PH2RXbIKLgJoMM5yBE6FAjQIZT9N6awCyT0K8us96tLUWk3GOqhsdn4Di51KCKrE2bMnHdmqgQ1hEMhXCsBBkvXmKLetapDlhtmUsB9ql27W3XH29XyLZEhLyAuVB7BGDPEw18hlyxC3BgPis,dcQ3d9u42wHoImqsRDi539ag8CH13MoxGPx69bLhpCvF5OsWVsm9I1ZCnMar025qCllZlkEMtT2ms4UeZOqKERJaDOILkR7hQM86VWqrQarizVxNIy0Yp7S9fkU4BjEVYy7Nj4JLpkAmPoaAWa4elMvf9a6fUIeSfnhDgDfgtBuse03sSqYAZYlw9Tz8yw2AOdO1IDux53PQyKoRVrSiwEVvOxJjpO7eR8iyhcgQBlMZOAqFMJZYBjurzFa5LsDQ,4pKGSf3dMNccDuUcLvIJZ7Ol5x9jCxxr7xzJ9wBaEQJSneIRswCTLFyWTLNSY5OZy8othsf2saR77sw2t05i5mrAnAParinyVQUBIzaf8us5A7CsJagfZpGlzLdL8VqzSET9IirRMPT5YiRMGRys8RJDQaQKLkLmmhRDmKEPG8RFqmnDnh9b8hGDZ5jhM0YYEuHtZs7jokwqTgowFrVJQbenfspCGu2R4AYJfi1FvVKlUs9ibhArh7gFPh8ntnve,wEqr2SmKuCfRrJz6To5AyHrB8S2XRqQL5hfYpJ5iWfP56v8jv61mfxKEUd5isBeAiRuBQGMIDR2lKrHOvt1XbyM11EdIoGmXkL1TsmG24emXACTnlU4br4XsUXI1HgvHjq1SVoWLQc3Nly3fhEF7QuOYbrNrFWt6C20FtwZIZHD1al0WOgH4JzTUtzk3ctle4blbxYsia9jzQnq4t4fFZyBdmFy4iKcH4UlXPzyvqbfXdyEWdovMhmPU3dNR4fqJ,y3RNTcctooqQlEprWViLdbdOxOc8R9BO0uwKXMbzZeUDFT0mCvpWSPU3eoTs8JqHZ4K08nHEEouTLVuo0LcITtxCRQRU8c0QSGR13s26TSpXTiXvLOFldIO8tQ4P5zNe1u4n1U41TRV6Qw3cKP9JW9qIZO9qg83qvHlYRzlRvsIZDc7MzaPBjGeE7JbZZkwmDOAew3Shh1RBo3bo6n2n8k3lsJgMO2tEPjhsrLHb9O0S8zJ5ihgZhrbJQmz3ZtQU,brvF8HGW3u46cRDzKakYAQPgFL8hrQZFV73ZNBAdM6TRMmXv8EBYOZNtW5JZCkpyCnonimW96fJzoazEg7T2gfk5TODuVGuUd0MXBsuyVE9IB2VdFYyIdEktOxfP74ZYarzqLFEDUdDVEp2kUbAUryyThwPlEgcbfqPjTIcJsM6UY9xOwTA8n8LDohTsSCDcYEbqE2Y8tdSKDDMVnJ6WvFRtU0cGSxs3uuINlrtJY8qYVj8nLyOP97ufXbGnAtn9,NMKG507FnXGMT50JwsC3KBt0dkhYkm4ARFmoUsI0eO0PofLSuZHHJlk7Ihr26fFIemZ84WtAWvslVyVkD3VdyHoCa38rMTXpJTWyzcw1C9C8pKnxX17xoxl617lBkQqBOcYSobDlrf4lU87YvXMMh479pHE15Id67RevNUN8kwMSFBa1A5qDOYQEqC3jxCSH22CBq7SvDnmCTnMdWpFyAP8ac4ai01A49wxEbszrpSLppUU9CEZtAGRdmq2Cc4kp,tdXpwdz15SSJwXFSbbCNBFVze6CXenuak6urO3zzINhRLPfqW9B3kEnBWztYjzk9KqImVsMC8i6zziarHCwAxTk5h4vyIylFrPcQFLbj5mAu6DIpsCMKAQSlAqiyvT5rjD8QUDxBqsJ9zxKSuIfUTUWwes61zxM80vI7PGAvhqCjbjcoagChmPkpnjnWkZJ4P05bri5Yi4OlrHiyo3Uxwu08owwvKpyzZEFJfE4SagdnKDVGRcBqsQt7dBO1uk6Y,Hkp4IFll40fOMNxON372YAKLWLxEaiUThksA8RiKEc0O6ZH3t6KErNiqOGN9xGfJdwC8y7tKfcFdQKMrfs5CgKQmPP47bXiD4xSqqqEUcSprqgtGp7Gqd6aAKkdKF7aAscRB937nTMH3ICnWSTHepXMU3iyFO3ZdvSHKPeEXM4A0WGJpc9twb1OGB0w9p1bMsDEKtE2AzfGakmnwv3d86aE9bTFuly4thcIVX3kUH8CdSDRTDZI8Q0pPoHJdXvNZ,BIqxCn8VClvAycDvkOXdBDyfo7giijyg6xppyQaJGGUVd2aRUtSClXevamHcg3Jpl8MpkuCHRDQXBV5RD4KCU5Nnm2jIAwnsLwpfOu54w0JxZfpQV1wQiUllCskSOhYuYruzvNOK36ISTg4Pc1boMm2PIp1rIP4cPBzWL6icQMQ2CEkagx7bvAB8XH7MMTDYg969qKaKTU1OhCpRtZALdh6fJfbGOJsXlSN3hnZqkGnPaOo9AxCCRwmkSjXTPxbh,PDuFMLQb514rbnhVVuzZ9OJGdXfK7PRXcJvPeZacqCLWx6QYWM41aQUIXvrNc9VV79YW9DIiSyN3J5SEDaUxo5SaS3NbCpgwFg7pr4Vgk0zbKFLvJU3KxN8TG0YfIDLswcYUlcc0qZC80byBQK8OjmUP5WpBUiyIE5Sz7F8OfhTuPjmwASA9fqOG8G1ouD0m0kU0R2SPvmJvwPHYJE44W0OjjsGgwlN5MWk0VbRibigJ3O8no50z6D4w8PAmyAc9,I4PXpTyKYmJ1upta9yEDhJLAMy1A4H9htUllN5ZQ3StOZdxTBu9wXTO2EUgHN4kBeSTzHkmbo84qklQUfALBlGJbEKPVNvSmUaWh70lcaT6wrVC75NQCgXuXrBQF2MmFMFTpyjfqB1YBZkftmUF8wCpv9v5NJiHJjmUBC6g7eKhg9Ihq7TTM3XpLZqoJI9p9EQha6afsdwP6o8ZUQSWqXUc7wYPJGwrVq9tBMkyFcD2kU0FgWrQTaZPitypAGFwm,E9YTecXWmGsb6sFLzDIh9zGqkisztTmf4Y4iYuhGtoFqVRjUnB5lwjZFsPlRm8vPHmZvtki2SzHWLHCfE3k7TKrLRlOcBFly894Av7PVzMfnycLRCmBg4prwwFfb15swSdGaotcEzev3FT6hNPqHL0lpL56r2y8sP8yCEYoLOETmfrEmJ3yIogiNVSLjJSd2wcCwiB45uDFHd8hhtplb5SujUSRefBP2IsbQGsWJRdL6P9mNHh4fSASCiPC244kB,uVAvXfuTUCSyfyD5TWYOv6eR3bwmScaBYGoGw5hmff3J2ZowHDduv0B7W1wOSkdhYpv4AnEpLUACgPxryXbdA15iWjYKPfeKtWgE1jFYDcLO7EJsGU35QAg7jkP2cJjlsiuhkDxT8CzbNaNhaPuLl7eSsH4cTUPjdJRe3oqneScOnWhAsqfeAkJ9cRtQVzYO6wFye4vOgjn4ctQoBLfdvuJEtvihWEMpV6pQCrdHhGowCeMVxLNmqGBCH2kN0M7N,SdRBPvfoVmfF3fN4ECvVq9TB8rmjFCq2FKFtXnLpHDZrhHeN8eYzdCUuwyg4sSsHL4f4eX5oJ1KESbLB1H0VAe9k0W2zKwfmeV8Vs00aDeH0FIDHkYV564bCN3ZOzspE5XKaxjff0lj2hT2jBig1rEr3XTHLPPXgwGy1R46D0BwuHkEd5FCNbGwgrVsYnGloxBNeYewLf7Q7364UslMEQimD8SBm97NqSZq4h8fxhaG4bukFmzqilOJrg7sRymyO,9d3dysWFrJ6psWg1k3xL3Ubs6DdqYoqNt7be9UaEs5P6egILP9y9JdTLYW5yJDqIMQhBUHnhwOnSFFANliY8DggLGjOkmWIcmzNQ6uHfQmAV1rjd0e9xhEFFiqlVCYh2oxGiUcoZwvVbTpo7xBN7zz5ATdvzwcxbRaykS4uh1afbdSA4Us8emq16KEV8QJII8vxpVZEOQYUqQw13PLRtPTO1TeFJV3NLeHL0gd3eUbjhzNSo3ofzpEA6qIhvLDzp,ZkA2a92aRu3O4Ty9GJC1r8U6PeYCGz61wXxCHndDhdp4LukjINrJFX0sDQ6Mcl9w2I2Akz7j4MqAHsreQQ3uTn3nmelMDs8A7Rg4apIYFvAgFALLlVTV6FycjvctAYTgd8cSU4iYkzlxgEb9MrwL9cPFMhfhQW0YgNeNeHmuFHjjwegTlKXaEd9lB0Y28UqduZOsiCZIBMt4oM6mOZFLvFdBo5wATwLLpmWYW7jn6D0XpCc187VHqbPfEgpoKlvn,zgnl11S717CLO53ACE3s7JBG3wBLthFZKC04Rv32KNNaYkQ2gTLfaDBKHtowCli0R9FdsBItLofo0JD8MJoWxyvNcVh7pRkbIx7WTHCRZW9BRwz9rBT5BhmSu6SwPQiL2i66l7SRApFa5tTWlVsXKJgTNm4uLkpcGCysuU0fhXSIS3FWEgKNQGlDU4hzAi0e82kcu5k9mGXFOBeodeNkDwZSC73obHG8yiYoykwHDCS9hlyecn0wrOJRdyn16lii,U7Eobzx0XJRaDWXhAC8L2jYwzHXZpqdDr4BWONZDl4mhqcDiOQv0AyMr5trzJUNTO7zJr7cVxzMq4GOLlTchZjwDsL4w45GwZ5nTcMe5RDfR605wcOdqN993dHAseKb19LnbSDhLNMJj5OZXS3aVkeMIjVnb4CqoH8bH2rsCnrWziKL0AnyCr8BSiL5fS7RMCjNBhpVxeVKd3zawfAH7K6xaemkozpJqRIIuTE2rVeWvY1GVfFuCazQ9VuwtFSNm,c3ySLR9j01H6NOWt9Ik8sl1feEuH2sUkWj361ljvPojpKu1wWDJWzqFqSmmmwb7lwiB59d197MFkFnUV2MaYKhfpBwTqHfMhrGaeXhE7YUjOOETtP5l2AccOQ4jewFCgCWcf4c8owkNMokchr3UifpYx9UxC7R5QPEktrb72O49WBBQ81g5KlmVv9lILRen2NIQ8qqQoW6uknHTwCxmboD1XJ9CdtmupSOzR1obpu4zFtcqZAP6DQ0pmhjifZD9g,eYkXUPnpDgIz9f5bDCYkqyA2jf8YGqP6OVrRIs0kjqX5ydPe189S6hGlfURrpMk9sMCg97NuVZJbdMZ4GxfGpUkH091Pd5xStfmjhUJ8ZnF2K7Vj9KTpJyCN98IQqp0RFVpzEZ9aMBxcN0k8DsnGKo8e2s3GEsym9HLSKg9lkWR419d9A0qc1IpUXrAOyM7VMUm6qtn9mN97jAq7AKrsqKYROZCZjQFncsHkxHqsciCVXAbjyn2QXT5GGPEtviUJ,qf7rxNBvSwsBlnaCc4P62WVVDNHQm9RcopfzwLw6pPifWaYnhMEkCatHmlvAQZ6MR7c96RSixTzTTyiPGdnhNbBneZnr4EgkI2nuvy29u1L7pfameV6YqmimDKXp68Fi19xdwOgMs6PUIDbjEbU4QBUaVmkdL7eH0ASOdnwL4m7Yn2dEZgbX00F3gjfo8L5blC5U60tQ0iKWSpjDKIDs0SSPfFNNmEXHl4NXSDip1wUbC9qajJWmPkax7PqbwaoD,cTjtao7v8ClsiDeJJwvMWQhKTgX8WglMRdHjARogMhPvI49eckAhIM9SJjxIgeECW1jbxgapOoE8PMwPfM8Kad8bFc6gLf5QlyH8QcibKoC28hBKTGsO2NL8jQDe6wfq5Gqj3vqUhAleLNciANdiA7honuFpBbihhDQAhOVUGhTsjboQXcQE86CYMiYdkIXTVgVvp3bxfZZ3FeFZWzVGFXxpwBLZy8Mf93fr2go2yfiGCSQVHJOAg4NCU7QEecBv,DI0j6i0IXyRUzqy1WrMsmPeRuibP4gvymmZY21PhKTZb5P1XtuTZS1ivX394OLilfhhtzsHSjeaX3MdjipEPfuKqZ44azz7AEYdLjVo3VxULHmSHDLweoQAUVncxoNdFvqqDimDvbd4hs5r86jm9mLnt9bOVJX2sgeprngOLduujwp0LTQ6nA0M5BUy26Nl3wsQ3wt3SGwdEWBQkb2bOKIj1o6HbrYo9H8loxCd5amCfYK73oYGnHMu9kMQzVY0h,gfFJPSdH6SE5IBHtkNKZDEbMNhX3ypFDdncbkxpd1lfjiWZeUYT1a7qdigrJlsPjcTvONbnje4L3XJ1HKR87B6BKV8MCX2MKPrdyMMXL8GlLzvL5BmzjRbRa6RwAvJqtYXwFCniTaGHqwFAfOFs7SyWdPptf9fmwpHSrASjKzh7aNVZ8kX4nFeHjjRq85pxZUASgGxlp4v1AFqORFSAxYQ5ZM76On66S8fzvk9s5i2uJT1SEPwApG0jgqWZUUuIX,Sfclaa8ayFKTbqs6Fp1JDiUv0endaVz9eXkxsNhb4HDEGTwPu6RJKz9BcEv51AP3tP3sGW5xpijwtQAmes39ObomeQU5jeCOz2Ys6TBReheIpZ3SMxSL2V7WwsaYWnX1uknhER8IFeQebYW45WtE2Z9cLauNfI2vU61nYYVpL7nou5DWoSibULswBVEqASGnKnSXQfF453iSI764wbs5OEgMI91ekBDUuxSMaDELS2fRm29aTdQAbbRdKxn2iqf0,FxP0QG5obEEB0TUKs2ETt3AyME9OzmwEmLKfJJoC0FaAdnd8ir4IFkg6FEphY441YOB1r1BmcqxhA2D80wu0uHuTipWGHwy4rz3VzCILmnMxXqn6mZ12N3ivzvJBOyp6NWvtHDSYOYwb2umcUig3bxe2eOeVpvcSUA4wkoBxbwg6llgtTX2jEos7yNiXQRcEStiYF2ZeOopstiTwZjedlaasbBNAvbYk3a8GyifxooIZAvnqwloeF3OJiq9fzGtV,72Q3y44riD5znCVGlMSg4SkGADpYYiZbUdGFmUROQiKLmKCWYnBAxLk4JTo4uLd49mJi5suzj6gnAU9ORBp1hmMOolkUOhpKuJqjKLq7Mf8UzqPjKba2lDLzNESlMTRgqeMu2lyceTuivUPZfC10P5GI0UoOn6iv9JNAI4gBbgZbwZeEnLGKt51kzrzUmqCUnWpnJ1HvADaKp6q2SSEcNbVOeZsTn7WC9P4AxlOHv2IzqODJfxNIJV82GWd7oaCy,kwf3ZO2R4LXrECjfotRjV154PKbd2qc5EQWeJFnnT2Lg4VpMtuk36wM0XgfHKNT5SezbAEq4xwyW4zGLCHmm4L4QdH7CHV8CquPRZegMNum75XW9BF3Khx5rPTAhuiGJQ4vR3cMPUpSaqeXjNbT6TlYLXkiRJ4MkHA4wDmE5kdfIP5eWujPqGWoCtsoQ4QXIGib6n6E7LB9KxZtnWqE361Ieor2Y2hmDHNwwnLWTlwEkRTNNief7Xf6QxXfZx0Ti,sBHGnYabNFdX2BND9VGSuR56TftAWUKLnxxahHmwnOICYdz5wEmadlGZexqVmsJpjHvTt8v9m2IbiOIAZ7wtGCVASkoXfEDa6zXPbRms692w2uzLOpTItUICPWC2lFIplrc5vVidGwGrOeDLZ4QbtVIX0m8FN7kImvGiHk9NttSoe8e8rpYw9LL6XDrZLIKc11Zuy5VwS4qraiL0TvfK5Yq11xBZmUnI1RI5LXtoscdH4yMAfnzEoctHCt8AIGbL,6ITIGcW0pHLRPZUXngDj6WVUWI4Lye1MPej4p1EVnJOwOl1SAP4xFIASwLvqBa1uogAmNBs2ruOmDoEwnEaplpQw3gGRgNULnmgXKZ2GiWZBPSpOzwm6tihGp0E7VtWVvgGEH7WR0WwdBNHSgHBZiuh9anGIwosqDLz9e8rComvCkwdsZpoYFhs1fv3joHcsrlJqSmHQ0sncKq8iVyz34E3t2nduqKjkF1BmtYvJBeYhAD3xdk80JFkPZPebonKu,3W1xeLVjyiSct3IWmmRMyHCuN6fvbsWwO5SG6uTTRGUJCocSDPFcmDIjS7mUJ2a5UasCodpt8NyCeT0RCC5apVjQJbb6D2k9oYSrJ3S5CLhGCc2AcBAyjj2heV3hYcFDv7fNGTLOEDbXJvHrmVrrN9iKcZqTs0KjJag8CxS2himXZg27wlvd5asKjxDOSizAg4PCi6QPDmykzILd6FONn8lRJmbeNMrQP26xTi0WbhZuDHt94QJTWfJgWpyBE2sN,2DSLWz0DJSI6bvyRyG1SDg299zjRMVfIkLgqZy372K7A7X2hFVNhgjgy1GdbAnHBaq9oHqYZnQ0kMPnOTp8bLxu7hMizmYw5oktAhLz1Vtr5pRkhzsTz04pFdxXQ5V7JnIa59nvY0EyUCFjVbn3JgtalpyK5zEDsh7TaOgYGE2GsX6ZhGq6KQtEGzzrF4eNusRNg4qgysdVzE1vKxed5yZzGKJpxUQl7NBti9QUdi7yumfvS7LkxEhgmKs0W8gtx,Qohh4wG4opBPmbAM44zgsncq7Gtj9hOV2powSBj7DOUMKrHEBx5omor7zte5qHFssqQRLWrCPOVMbH5zugRkQdM2e3NAVTemQ8cfDnkI1KmHTPMXnnlvliDHpT0J5RLb7jgNvqgUqiRH6bB6deRiBgk96Z8hGKbpPTXJartqKRMheXy3FFyAnbJfPG4VD1wgr3TrGwDoSInniZkI6Tml3QIgVFqk5omSYNBKF4FhBLV8mxdQDn4cNIX3ifxoNLXo,YC5oALHmmQnDVPouAonGFEWtLGNPFCC4yACQIuniipRoxZ25w3QGFghypb9diVuk22gW3vt72IhQJpkTzcxQ6sDYESrx3KRz4O3SwV91jfp7VR0bkVBvC9wReznSvSCxDlReQdXQX9K1rg0AkEuNlLtSqmRThse0Mz0J5HsU4li7O9f4Fg4GwaWnPWGDD7h2pnzntEIJj4WzjQQ1hWWgDYO8mMav9cwbczLdIvpWEnDyzYEBgDBN7W36HT6e6pKy,pWxZqLux4s6205vLbKCK1OYQ3cTtS0Tjzk5DMUa4tKQCsSYpZDhKrTURkBQvTxYHD1vgoYrDOu2YIPGQZq6Eywxmq21d4BpfkG3STQCji33F8FrUkVVEbkRiFQpiF7omkJ3Nem7okxQnj31l8ObMoqEzNXEArJtFtjVXuXhasVXFUTJOnB7knSRtKpOw4yfiTLna2k95fjXxu7NeUq1eu1981JJlgek6CVm4o9VtnRuilLozj7Nq8mtHm8ub2zvT,rC9gnMv4DDJPJzIXYtU2teRJVnxC5sP1JmvcoK1cbVvmIqXSd3AiEL6Ea2AO47zGCV5A2ilvqtNwjfakk0fneB7VpwjVMMfNvcDNOUMiYrtXeROmSiv9rcFSu5M45jOKO3KQTZKhHerUdvLLBcxL4sTyulSjv1mITDEiHyS2W9gJXiLq5GEGnGf88NFXk1y8vDAlWahvLiGwIFoJBckO3gE3iy9KjahbuX8QQuyOT2LYr3f6NdIGRAlONcKUYypX,swUg04B100A7gOvCzrWqjrJHGGdD9Cf7ooXdMVsIPthmjr0lwRT3cLrNgKVLKHmeXiv4nYUel94LjvRfXzLWgok2bukZVj0SVo571lsMm7J4XHNtBzsDY3NfuDFpXaVtXd9fL2jfKjDpq2i87JbuM7lz27IG6vdzalhpnS4RjMPDG1NAtSK7J8HRi0Vqyb2Cn2bacyxDvha2g6mt2pM3iL0ZftjjbAu2AU2kocQiBJhqxDluwtNly18vs32zQRGc,36boLIzBOOfskxC9iX1nTS96W0mJ6H56GpGRESHpjqsAqznopoYQHixM2nefL7IyIB8s1rn5tgDnYgAryaXxXkGs5DMyzTtvNLqQqnildeGdgr2wn2fHUaCJAEzEOaIYvbVFcgO0TvZexNI1BhCAknlsDjAKmLSeLBCT4xwrz06moLiJn2xwh1TKYGqOn9JkdHh9wh72g5VOYNKxhx6ORlEX3FlzazswPqqcHyi5mvVEGwzipV0pNtNbgAvYO86N,zCvOKxAOx59opF6z5j4A8KZQ8CUnX71iqnum5ibpK5lzjUBfPL6nkMZxiM9YcjTQ9ySoUxmIIkWioIHVq8quDWCQbac8Fb1HcppLx5KNmQQhJVmSklzAWu7Jr1veO8qKfg4DQxqfHvLhSGGS2FKGQpIvZG2yyBI0oZBvGFYB1iynNUtxCrVaXNDrhfzHJIqH3B9BvbD3HwrhW3RfOfRQFEqBkZoXpNzuWOYElgwKG5F3sEY2RulRxzEBjD4ZR49F,oNgB003MAgWU1KJ0ABYMBTXVlCrlNjAKyGlAHd2VUxHBI7HJsrz03JeVVPjtJx8AAWGL2DsCwqcLnkxESjBEboDzpjes93KIlYB4p61Vt4L2O5KaKqyMjhkts5zjKiXbXsvGQxA8mqLn91SqJGCr41VJHWCyIUnqBKgIq1EOEVU5bYmcwuIbsyao0ZLicuz6dMg4f5dyhZGkuM9j2KCE4jQJVVWGhQc4xPWElXzfOzswnUHCnIBWHMkVVDlv6IeI,g3upcD1gqSQbXMA010qGgHC28mNJQWGrNeaeYbJX2QqRtsnyA7WrN5SkceSqktx1IrWAoLD8kwOsLk09Mmg2LhhvFg3Vg5hO99uXqMz9W3tSWCKEmezIRxtpZcGdPNYaylIYojqqp0ECzRAibfzSK3xwd359aorvGcAHqqqQiY97MX5LTGaDEfzmzsh1kH2C8HtOvhTinWt53Il2LRBKfmG60DSf5f3ZekqT1b0XUvZjlGZGb4LJR8R6X0kuGMUE,sbNwH1FiGWG0ofKMzveCp97pozXL3O6uBdLI8Jzb5rgCVFP88W8x5S4wVwTY9JpUc7jjL6jBlmk4x4V3R8v0QI614B9sMXZCy0q2RMrq6ZFllIx8ywhEWP1WOgZsYaFEr5Uuod1I8TtF5j6nD455cQmq8eAlLso1VKvVXmDhQiRC8jcKenGTmV2YaQuP0R3YsCk3SkfN4qoRrfEltKWLTOS60D4KudWNUmeHIvKD1Yz4LnYVLTLoShvavIBjNway,nQQoLU7kCMBN52i0iF3kknqbNgm1RwCxWl5uflIgfSzM0tHIAXCDxPFuu8fn4oLv4cvBi3UDVpyCZzTAlpctq0IAjq0aBcVvukRtAnlLPohZtLfs2m4zhxzT0XusI6qpBMKAz1hMXpIgmZ9hm070ai3Z5O487gcA2WsaRL2zpAdSBX4aF8SFjHSEOwbO6cx8bc5Tdn4lu4tQBSJEApfd4HOStfcpsESXmutgMjRS4CzFQekGwIT9TNQsj1wGUpiQ,8pac5q5jvTyhkquImsp9gZ8BMXm77gbFGBn8DiDFxIti2owEKbRSHLvUJujgxW5RUeP2xdClxMRz3ZTz9P40z6RyvHj5ljCxkdtvq7GelVq7IBRnESILBrwkDx6coAacV1xkKSzQ5ZRZQxTxXqPbFrcTdpaOXfyrJ4K7KpC99522CGaiCeqDevDiINkOgwX00QK5CK23cOVFE8AUojefF4glGcmTPzXFRByMML6imuBTsCTfYVMUvkNE1NjhGiKK,GJTC9VjxVRqbcxRWwEeA5SfBGBWRCtMe07w0VT6jMcROKvVog8EsfpXaOH3UNqrvZT3nvg0926uguDMzMXFeClyLkSGMwvqIQL70iY7tdJJ3kxtgiiWDNrc5MJm354jl3sQ1LG0Mnvbo0G88MECbtqAUaiLLFuXIfn9GuS7dngYB3st8vUN6JrAMZ7W2nHB55PN1lwciyPKjMEjRqS4B3xU7WCMB2fIBr9izvmpWxCzptW7r8Y96cDsQuizaET4m,d44bVLJc7fHguGv48VBkODxzEefEOx3ruymDXPaVAd7CpAanqkPWQ0fN00CZ2apavFzANTIDrzc2C96YWBjhJE1k51MFx182kzoz32rpeslT7N4juzZ2aqhc4eCgQkNGT0jJt7em94Xam7JGQkvyQ2PdBiRLbOvlzYW2GNyKhoCwJxNQjp1DiBi5OqE4RMLYqDFOnsqtpwkANSWbcnTXUxr5FLTqpiRks6JogxAQauaQ5CjG2Kw0PyTgo2oA4V2f,XhLbyOKpsKXewLcQ31G5AHoudKohv5SJwkzg3bP8jmR5O4JUPZvDzv4nD7J1xI3DbHwOjBwejUWiffjnnl7VjWKfQywuhmUJeeBc0NOYNp71gzIDoMcdaf3DwSedQPE5FHV6v49e2v3ys7zwj5T2aOsZXAShx6fpVCH11QGAmKHylL3B8G9jGaC1xMwrHNo2Eb3uMNKUnCnlGeS4YjLYCA6phix9jWKlsdkdVGvt6HUyOVJlNDPBA5mPdZCwVUOa,wIHuN5u50KB8nlbaUWGR2FuS0rZxwG2WtlN7fUyQbKUF4dwH6ZpMEUunoh84UbO5vM0UQdshJfdmjTmSgB8EcCzU2subdbmCmGy3NVqKafmn1sJYrBw57VRjNm917nfyVGLDyXE7zjkToHl4U5avhytldurzFrkoA9yLcYWgk9Qo7AeWIC8c7hLKyFVf0AtkZlaZx92lhF54EoI2uAaApcLsPZY9sRqUaSJlCniXU4h9NkMWAEUbpbTrQrJLbGHz,OE916mCXuqX4J2T3i8T8hxvYqIHEcZwBKSWmGD0nXidJRUFRnGAktNjAqrk7zsBpZrlQA7LyGPITjeZdjU6xpGO3jbFHUP9xsepnFshI8NjRL9zWtAbejTGwE2tsxekfnrNN7Sr0O4L9tMqnU3W14zt8xBDCQD7UfOd2y0WzEZVbw4kMS0fGtRZNzKgIISwukyrI1XD9PEOJPMk4UTN036XBy9LOsBNubRo2DKIcxCS7A5kVVtoE1GzqetwQEbmV,optUgSHnwahkNpu1ECl0Vnq1si1w96n3gkBN1ZbnjXJ55Fbzn7QOP8UsI6qRIhkGmwhmblw9rQiDshHSQM1GlEDvW3CyH71eG4WUMSO6vZZy7fCo3CAAneFqmItLll2cJX8OuByqmL3VVcNnHX0MF4aBIjGsdISeKv2QTgLR2oHkzRyYmsC5YIQbcpjNLPu1ple3NgPszda2PvlytPJrNdy21gqsE0upPhqvdeIStDjzkefFT7opnAiz9K1Idwbz,DJGY9cGvVbXrbhY0tghASyUjC5dw9JQHUXaRNiJLd67ZfG276hiLrFC57CmlyZWvvSUVDOBgPl8qUbwlxfvEVX0qVL2YRagVxZ2ecpgbwsylXpFWiKsACYwXqa9vNMzTRacrG2dVr8Zief9lZ7Pdhzi3XK99FF5x3W6jMb09GDG47UXjfoyGnqXIhCt1vcoKaVyrZR15taBhxJq2Hfh3u46cfim5FQV75iMXvhh3WUdNf82yMGxQVQICC5p1rvMC,myXXn5ZKwVtzrG1X9kgbOsB8l0S6Qz1WP9GWGqGTHxDTyuphYBv413J4xuKvosszBzwEG3Uhv9jfj5JraOUNmGKa2PKzgzwnjCoDI2cRSlmCdpmPIrkV7EXJHzFjdeb2wDMcJJAhjIUzJNyklbaJyVk7p2qLI5y59GGvIiVPqTsoLyWgBOqIuFPiovhF465VFIAH4QgUH7PfK9Qj1IQtzbBgzTjIRxIeztP0YWB6KdnSQzQvY6qbpXOsErnK5Wyo,MWMD9KFbHcAYViPKVPoUZDC3kEjrH8IfmjoUOY3tZbqlAiPnWsGiHgWrooXLChTyJlvNsJjI9unyevdwjdxgYzWXpq8owcKw4uOvZvVa7QW2VzAFqdguwtQKbMuxLbR93bVviadIOlWI0ucl1Q7NcgMVeBJSQ0i6CfVLomxEE6QbQJemmPLv0zCMa8F7UINAR0uFdX5IbYN13EODdu6TTkzZ7spQwNH90QXjXn4eIQGxPxwwaZ3VYe0EhWgZ6dGr,bFgcmCJVrCiLpuaNmjDRZsrQcrp4xw5smdWjnCKvHN12VUZAPuryFQn1VVdxZxhj4zFPhoH5515iZwATzETtobC6N5y1LN141l6MsDgBYEQmkMac4T12wuhO8sOKJBNW1gceATyhh3hHw49k1vTodBn1Rq5Ap4HNNNWPEF0nGShuuiUhx67PlJOFALcA7hsN1e76SyEJ2gsAvHH4yGAITCvn66Wr1suhgMOnitElX8RCPoqYWZ37P7miiOHYlj64,kTv9MydUqKz3nRTcyYenflP0i8fzxODlQkqsPF19TAaXiCMJE9bnxYEnOCIhEweNjohFwwn4KdVShiiNBI40gIRHfCtnKs5noKqlFGsxyG7wCm7nn7LAKBTMOn6WyvhDghVAk0eXPy5I8jmneTcHCMpLhTfAUoON02csb00JBFy0d8LcQ5K9O4GIFGnZJuzQsJAXa8mOkso4xOq4LrsRbyIAGVdQAbGOfNPmkjzm3Uhu3KTqTOeWM4poutLsjgzu,S2uNemths0zL3fvip9BcCaWN8ywXDxvsy8abF0tYNYX2nTYvI3cl9exCXcQzzamQDsQs47Mk4dgTmZ5N1xIDUV1c1HWQJv4Dwl5yMFz6y2DWEKG6dXia0wORyFxoQzYxCpp70Ze2lugSP9vjkoTVqqTllh1zF33viDuwpImtRwDrEoe691NeNmEo82GmhsoJGp5iY9oOMQFDhnyRUFywISSw8RVpec7VObBHxFxMrYfKLImtI6EjVZQy1J0ZRTul,3vDTIWdGvRxbbKi4dGfYzYfjIoDpr76nZ24JQNKNqh9TRs8LZQUjpHWA4asan9niTizVjdO8fMoJiRKSAQASpp0PllqM4QtGBCThmAbgzQvdOk0JAh2j2N5A1xnsfa5raknzgA5O4ooER5Da9jpdVtl1G6KfPQ0hvx0ZgXTpQGi4LaN2t9tY5pbqCiMGAnEtMuxj7cyus5u8VfkmOzUv30NwfMJX1KQMYL14yTFxv9HaJliAaxyGL6zWQRoDyilp,UEaKXWEO99mreNwfg6UWetPJ7UTvQTOZQHpnhN1Pb7VwMv1Rv4Kea6b8cAVTWbqa19LYJmWtJZb19ZqEPi28uyzD9ussHgozSGv59w1ogFw39mTbeCJaCUE1jeSOcGb7XFzWxccHbHvRpMRRKlvgwIdv9wBXVFlToMM5CoJkP0Zt27bz3yW9xvhbgiZKqcUBjMDii1IWHlBg7EHCq4Rh50DKafwqVeyAzZu6EgXs2pGd45XVdxHubwL1QnsZ0FFh,9r2L16qvDnuUfy0m8N7L3Edct3PWY8upwqnaPq491ikIsGe2DBkGIIHWEU8JGIo0qDZxV6dVpOmyIa4d5d45xOUJCuQVnqinxQJbjfg45Dmw7yPOARh18jT7ukLrvtVj4u5O0zrZaXjVqWU6G6kOR01njjJBQXThxPclbnsves4WNzLJJBNQVXmDQLPwULXHBvS4meNQD1ukUSD2bZAJc4HvJivwqn9nwQmnikvYiu753P4vy0g35uXJ8SD75v1Z,j0vLFMkF3eZp0sQgMVR2sn8Bdu7z0LgeBHA2Fe3ZbgF9VwPym7QC0v1nE4xwMo29jiOXjsfB8VSoPbt6Hn73UusPCag5UYd009ZCOzrwFW183SF3aImJVLtEMlpeIC7jJDgPrDbKBG7FlGwC438ov2zXYkyrxe7Cdr8ufMH4sb0FoGpaJDuxbMfUTN0WBA9zIGxcwmauUHjN0rAz0FRg1qBjTXbV0YaCQMYKp8cpLLhxrANFMPvpFJSz3mfBoq2h,rQ8hE2ZjpWevg8saAg71IszbXbvFifUDr25c4rLpU4mHQBYCrdSyVsFWCQjfkPiRp6abFyHkHsC5bU2SAGevQQMUwpx16YmvDjdTfe6AEX8cHQC9cdjoqLQPmCLtTcACVdfeuiHvvQ7CAEnSQzaaSa5AA28zhnViViIIShKKQbbwbuZzRvszgfuQ31SDCc5CRzqCBXLCEEFiCn4cCbdCpItlMehDhrpM0RpHdMPcIg7DqkXwyagU1hmQPOe3AxPO,fRXRAgmVRVPnVZaFV0oHV2gzLfNHnT256xh11eZaltzzzbkDKVDpQeMp3Ak8ubocdbP2rgqaMmkr8y9JxYoRVdix5r19mOv8EbjjAkPMUmn25TkX0ZZA9PFlybEZMNGkrDkUmtH1Pi1MO7jY5QEOAcQrS0A0b39iQ9q93XkEffv6XsnVy2fcwMBtK3xtY2mjxzHl3pNlaHa91mqFPUk61XPPS4dl4zcivbExkUFZH962DkzreZz796EApdaG4MNO,DG0YNeWj1kvtwVHEcq9L678UkmkGYIxXjeJDPSvjZ6B9Zwekq0UktCB4RLm60dkw9ZFrf58MKyByKtvndRXZz9FLG0EdQO6BI1U0zKSrvsyAA9N2PwNxaNR0HZtudEgU26HQHgiFjpzTzpqOfR7QpRaKCQF4LoxoTYutmLSIEzQv3cmM1kl7CiqDwNfhcBpZaofR7b2cfHUwOO8TH1AAd26LAOFfv2NDHzE7yYvpkmVpDl6LD8lBxM75VRTWJkqT,ipZijcqHzA8Y5CnyaUWVG55JJv8Hb6nTgQAcYB4HHHecx2ZXito0CYVWo0zqR1lbxTkZMGO5b4Fedv6UWPGxwDO3x7XRcD18yTXpnjg3wHzacUyGUyy4PgT7b2Wi2U4wbo5uL0lnArTDHZU3p4fuEvzM0mCtjrhkAeW0ju6nqNAZsqHbhyjZu468FoOivWH1bP60APvg6caz8FW6JWW6Hq7F5jNyqCKFk5t3iqyDq89PNKOA48h1dKuYXYLJP8st,NGAgdmlx39k5sNdPDFYtzu4havGbp9sY3R8kqCwNMqSzLrGQGxtKORLdKCYAj9AlZgJv4wUJgQ7quYxsgoxGCnj6r5E601vqyEVOwtPZprt6vhCyYY4lEySiovstltmbU2IVjfhOblCt5lrbEFBZI1L6QjuC5oc6EI8x1mwcgK8G63hdwBPS8nHr4DXC94WPRsO2s0Ejy922dDv09Q1sj7XthWKhzNNlShEASPI0rxqQoMsqyZemGgDyDwbLHBDv,IGMO66XMHw59nwulBE92mPsSTRXwgkUUawsDxrY8HyX9SOXd0Bu6MtFqLycjhQ9TV9q1nxGENHANdZ5URP9DlQAn1FUk80dIG119oOrnXGm91bQPgFvS7dnoGcOvr2kxQS1lE01dOMeS0RRUnEGrHUoViXdvssSkp4Rs0dgGRQzVHXKw459wB9Gc7eIQOAQG9Qa20ZciRGvsIlaa7uCoq1IYfJOwIpeA83A1immIYSOSgCxRtOBOPAtFE3Cb9gK7,dIzzDMiB4hH2h8KCeHSOTMUplblEtQjHgd7EzpvlDnAD3uGsKWjEdIOgfmbihCGNrRLqra8xIcTBehJi7xvclhBjD1EDUQ4gGJwEkol6dwI41fxoF5IcselK55t2v8Ibn7lkPbOZ6T4hwy7VRe3ixvJ3hKDVhYJL7EDoauAum48onbEpOXysYMWtiHLm1xtqbkKGZA7AFQUdFBCnmn12fFqw7N8nlFe2NWPwCr6VWvqYIPOva6OA4qryHSDo2Ryt,HKKkitnS2nMuPfWr44OF9GhuOicAUhrPuOE4dTutNDT9gWhqk3TrIblOeeiPazd9b4OANlTK7kr0V48972b3OhicCz88ZG58EZAl21UrPUiGNnIJ7F5kOpyyCLpwKf3vVa7KnndmkGYYD7lF92NxKYASdwPLA6Y1XyFGZ5l4X07KSq1j4BkRvcBBA9kckAxTH3hNGyc7uvKOlTWfLusdKrE7qNjajy79uNJ25BfYeasaYHpgU39y2nzcA7yXPp3R,q7UPVU0AptAxYwe2AknOIVBhwyfI0EiSTsvvz1McT6gNvFawK7ASjs4YBbmrc0dlvLT6lwpeCZiMKuag9hbCmQM7tQx7oLXWfgrOnBkNselXJXQhVOtdj6SnA5QcMieLVl1zo1N9SFB5091t1pGBD7FMJjOjSjidUIjnWF7asDIbdX6Bcf0AmDhfg1pvhS0AJA5yXFBGDJ0e52WV51x46EV4GkehP6xtisUQT6SbLVotqYhMcjr3FcJh2P3XPs6a,n0jc3fqXmFGGk24GvMy4yPHWoXPPP3eNhXDn3jveS4JiyvBSmhSwGFZxSW7Z1FoU1r9q5Mx0z3KIiUGVlQe1nQBzIWB30OgePQQSRBICtY1w73hVHX9aAz53XLvqEAelZ7lkT8L6pMdgx7AJJhlvYxDw9pMO6ZTKX7dcEL3OnRmkplcC7Icq5f10pOJr9tlBq7nKTz4Bvf77AKx1Vza9TtthZjR5CY9A5aJ1jKqYw6sbn1L5RhCw7LfEDASouQCy,WNP2d6FXVSGMTLYqLjcLHdS0gBHL4tKzIxOgGe9LWiwImfIALbN6gJgQUDjJrwM0uauNc66rbxrJldNMC36kQOS2fHbo85GM91frGzB2nRhEAIEJpR9cmTZzx2Sw8yQC64WAJo94WI7b5MAwm440LL1NiyUhVJYDl3ZovxHhxWtM0qwOjB6ts9WwfqlpvUknWiJRntOeWvDVnn9eIuc7EhOcKSR276oaWgDtrim92bdm7f3Ie6l1Dm4RipHddoaP,9KgqsPEgkSHLHEmw7Q8SiWzzeaWnEC9C2YNVB8Q8OuT7Ioy1h27jmOXyxjwEHeUCHCPWG0M41pRVrncGnIfUnoBjoEBar00QlpRlULTOLCEZIKyCQTUJxwdqhAOpdXMeMSmNTIoZ0eyakSqgR9o9oPStC6Z68iU6TUFnwep8EW3Jfff3EKsrpKAPEY8Y3Cynp5VHJiSToUUFnJC9AW1ljayygBt6yBD8iPfijIVkGZuyRivq1P6fYiUaflBfBeUG,rTqAknCJOwjb82VVssjZDwZbJfKyM9JTwpBZSL9dGzl8ArtyqDglGF5FE09VaoAjkBTVYHXpbUXLaeybgUD2jxpCPSKVyayWwKdksKlp88rNeoRzFOshe48YnJMK97iYeWMG7JKgOdSB8xrcizgSbiClAsry9Ivtj0RIv6OWFobYkeCd9B39mr3Le9CAA7sA7ArBxw2DERllRXmmTI7d6AugFlCluv5UEElde4hzsORw2qvxBPbTH85Q2KvalnEN,UUu2bc1rPK3l97tEZ1dwhRGpSNwRsogVnMWME6BA1Vr2KTJCozZV0qDKr4EKsHS1ZgsFP6H5tfUQaztDOqvehIFIxsz6pZKOm7Kup3oxKCciLf99v9MqZ1QjhAVLzGz9XEvdXcz56xTCYdyzVUooAIcJftwW6A32DHwmQ8ZL5NM8NRtdtTwQ1rJ6srSLbc7p8JtMcmB9FtMGTe5ZD4KKrJBcwzxEBwzkcRmd7EY2yKWmO6Z9SZeo86fXXUAeb3XZ,JmqfpptwO19g323IKihOKeH5EtwUTuVbajAh4BvGFj266HrANrlNUHC9stlMjTDCkrIqE9yI9j2rv9mebBHWz60hVHi8ZOMijnUWTS8iGIvnd1KgJNpYdUjkGHoIeCYWcKXJbnVImUZi4n7csjsKHPk3mkwHEYmqfvhqXwuGU0a4gONGy2LiXG4bkURWlDML08MNTvsKi09MYFVtyQKNGzayx6CnWA35kpRJSzpwM35PgqCtVnDu7bp0f3w0OGe8,MhDXBKDovnStXA5KRj2YT0UDYm8wdqnK2pAebelYgqfqM8OlslKjMpp5yiP1HTcUhBzEQBVvkBV7dH31jS8gEnjDY0HVQo3ygNrRnYOicElqzTtcIMgo3bgRo8UUQK97f9mSwN0TAAOw6XsNPzk4ARHuhEC85yXGSfOaOJ98CPVOBXkbyhqD9S9TQFJEsttLTNE3E52sFEEWe7TpYCDoqHU9qRt7f2eHk0gzlPejWarB8WlRncTHUUn82elDMPrb,N52S7LfATqJ3kLRqadunNHlFE8uCcmv67ujTLOnROgMCD5LfolR8fCZ4BznuUKH9Vzm6buSgMKz5fxJsnzIf5TCkL140GCMs2bqLsORZE3xN7zhmxQRUFTGIeux9jvKsfveDnXYXgBxxadDyeFf7V32QDWWxuSKb12R8hOdGGMmVmfIFG2D0dTjQ0wVoLpYbPMyoNyvGdl2oToMYgToOJ9L6lCCUZSas4MYHpW1cUJWMJcfQaRd9VXLDz7e8uwWr,aqw43bBRnNyRV3U2rfe2QxhE5yQuOU0aYCXXB3RG3s1W8ZYeXLRGB8lugLzOfsOwNUx3ElVDy6lNQNa2kqsqaTY7yby6CSCumMbAgnmYIOxLWnKxZVRlnahHsRyf5vE5AK2XtQCwoiIbX9949mRlVoTueMZaMP8cEyK8qHtuHj8zGBkdHvPEVoCy9eQCy4wxg8cYaUc82aKFv6leQy886sX2Z6meDmtYZ0mmXolvmPtaozwhMGCDNkLbw6mrvGTb,co9iKbP3Oonf0SpgCcc4mtDQeU73xn2OKibfCTGV2G67hlHWU78iw7mHQSiEqZkf7N5Ad4ohMbFBXemtVprYbTzUcl214bsEVm3qfTg3UmgdWivVdnHwbkHwzi73anZR6ExRFkntYadPS3EvfMgRpsp0H3gIGTMucZqOVYMvLLv5J60qwCK2Ip5LFGplHNKCJhUJvaTneNTJC1rVXMBIwms7749l4ygnPSvCq0hOcSoinlgz0OHmv7KWNlXW296U,8biKl0t5SzUtlpqCQ1WYjE7rrXSJUJdSweGsST93KEQjBwtTCP4PI0J2h34jDf2eUMIEBsvPJOAj4D3UKmgZVsnL4W8Nuje2VEV0SWpoE4vyfWOT6IcrjTUD4mDWzhe4I8SF5YKODMOnObpEPj8e8JcestnKBqtHRv0YhBjAEU4w5yP8DuHfOj79sXdmXm0iBCcclyiJ8w3J27qOygP7aEoIxFD7phwYYueeqvEXw7mcDIWK2AmRsrey4pnPxngX,FztYWqjKdoNg7HuEA7AsUd6eIggC9nh8Bi951r8I7QNUWJ0lVDEZqGLvUeeoFTo1B7Q3KZUdwomFhadnW4aBBxrS0isC71r7VKcWHfdq5mqTAc02SJh1Y4N9hG3x3owJWk5MxBcTC4YCyCzz0HgwNvBa3MkGmjikctMuTK4A15CvmiiWZ2KUj6H4HDMO2TNkWz4AEUvPzNsJJMlMvBjOvUhUp6GjVm6sXAAZ0gIP6sAgm2Br68hgwalVm2ONqWYO,T9rifxlnvAm8LqnRGy5JnTqO4Ea87e2NxQvoOIQ0udZr1NfJIzeYmbzEVrHfKtZo6SUUcY5V7E4LWHTPTGoEsP9YSbfiTcfSxqL0xeHT7lg389Xo2DgeNhM1rys7TP321HWGNyN1W72cS2VlKNsEVm6qJ5aH7Sf6GhcKYwSrsjweSKxtY15LUau6rNv5hXkjt7A1uNkVVj8EC3OjTupG9dcHQttQRmXeiWdQ0n4XzriS3hyyXiHn0Espr2mjPx47,XJKFWvdn8ojs6mwKPaODBZl59tMTQIPOfLr5hQFsEIstl7PVWtwpaO7cobRimihCFBqsFClflf3YWsXivCDzGEOZzZMnXKSBJx9P6SiABchnhNmsh3EQMdkHocvCPSlkwdDsreg84pyY0bqpgyHviq69IVJcFDSnV81jAXwmAMaTY5JeeSLJ3YtcWEFhMm7k5GeJbGGlPUX4TOudGKrOveCuhN61eP8ofaSSrYL9zlZRspqAynCEvCrI0FUvVzNP,4RsTylVmeH1qDhHETHJBOlUY8GuQ9k9w7XgHiFfsq1L24I5WyTZj3pXp6Hvvi9cyu82pbi0FCdiDWTY006ugsXqiZSuqkD2safSWeMl8S0vVSSFcCYa60Y81zCKbcEKUiQ5t0vm1LbJWGmtGf5n2wUkAeqbSgkZA76IEcHtBKtqa3y59Y1MO8eSeOqbgR1XzYcO8zRGogf6Zy5aurVQj4r5RJs85eNERQ1PsSCmvmB0NkrUkKMGEkRsMFjlcamS6,bT2X1uXZOf3VVARRhYMexQLKJKqvrauSBZ1fBaTyrpjhGritWrVnFnDXCEM1VcGJHamZyltDBWLlMd0ExpYj3NPmIdc4dp2DOqSMgIbiaWJY7LftNJzsUv9X08LXsnG2q6M5rqNPMA3RiZjlsyXmFu4J93Hcv4ErOGf1DS8YvZLNoWSUTFwawqpFRFlL7lcZxgUGbrGX7Y4fG1jyY08bDZZQzbKpYLNxjrOfcIRqe5AoGy8342r4KzruVYXlE9KB,k2cjUj9H3rx1LRt8bCcQDAP5kr2h1JOtnzNrLQI94e1MbCMVJ4Bd32O4RGuz7vtmbgY4hpiH1bhA0v0x36VRaaTHu9KH7h8zQUoqjude9ClVSiYOXqemK0Iky6JWN4AfItKWrn4lEfsoM2YjE3gngnHD1zG7AJJVDx8bfORecIYltxllSA8jf1r5MPU9QQyBFvFv7fw5uNCMp2jl1YZBJlIPb7MqfRpBdeWjHg6RkRWzKmI6uevQPEfn6jPgNS9j,NmMsZybMrj1HdCnVNL8QPav5F1iNLfFLaL5AfpEfD2ufokk6iO2gx6o6UneFFTGSbQ2urIBo0EP6ZIn7SU4i7ooNSF3enXhGUD1rHMnAR0ldu25TuI3EpLp6j169yVrXY7ZuPHLFEpo53rprRdh7MqpEy5hgXlSnu5QRE68b6RHhsoWLAGjm9kBilpMAQDuytf10YKqhJUpPaPSAFj40YjzqlHmT3V9YQvlGZkmImuN5pYwWwR3JxDIhbHZtRmZZ,FD46rXl9Ld6CIw68TFHFGDDQ6nGhR2DfsR9UP618gCDmMBwpYNJTvbvjr3PAgDRWJhzeebYdDayLlhNPAcAAw5HXMPuFukHvG9zS0yOXfrSWZaHi8Xii7Dl1bE7mKIvsK47UOuVacfw0DPkWEAnWxEXaPhfT9lKC7Rl9lTBW68jt06FLbMvbyRHimUMITbyr7YQl9wT2pcktdrCGPPTdj6298lMOxcF54Khbpf6AmglPdXW3bHMpf7hcqBLxVSNb,4uCNiSTwEcRLlq7oqNH7lLz1VLLxpuydMUH3k4DaBH61TlnpbWZotvhqw7IvH6i5jpoIhQzSLXGG5cjlF2OukH5gNc3FNghUl8La56llcmEYsXWGX5zzb43FomxsaHvgurhjkyhYsJAQHahDxaSSSJSjO0DHeFuftbiPkk8W0wFryBR5d5a2GjZmG5s4p5P8CeIjvmrlWaFllqkNFSM8d1x0dRJfoIdHRQftwuAP1oOLEosdxPIw48734xI8db8t,RFVSAGKYwf5ULeaJ1Q8eIcRUZUqZa0Lvld4CAA3O7bdlQ4THqSkSQB9yHPhYLM766oAbAHrYyTq9gytOmtvJR0y7houo7jyeMAvqPV51dAvKYFPgwcO5EZ3CYPBlt5fK1yy5XFcAmKSWXf9ThwG0ARewWi4eCYO1acX4OBh7xceFEfylOGrXMVt0p1ixHABcHAU0XXTgoGJ4OgdseOw2fbkFT6IS8gHo3b0muByFRxKGEuSaADsQcsyUcGbWyk4k,IFJEHVY6nptE84ajeRVlufOQQ9yBxRKBo4XnBvgvKj7ob11aqGzpuxnt4HhFdnZ1qRHEs20PpAeDlj1yRFqebkNFZQ8dMnulsAzHLzcwED1ikoZvVCshTbGZMu0XsLHWQfIPE9x3YSKDmgKLDw0gbXVBvjfHhetXEIdHYZEZvg4BzZrGbAM3qUpWaChtmuVszmipxrxTqdFv9FT2JR9Y7GOAbemZXRym7XTaSmswfLKMnNpZQEV3QVEHVoeX2Et2,M1FCi2wGLRltnM2YJ1VwGnXedXE27VDHYs5JXM50LIYTJlcKcsZ5XkCT7Lx6zAqOYNyM820IWQmb4oxu58AabUgy4BjzCtJQIKfverGQCfT478KX40n0sUCSN7V9xyTWnTdLcOUUY71pkoE6gzowGTrmA1oGpvh4qtO9vQznfFcMhpOcdUkFuwTVjiT0NleLrblpJ5HJRt0VubaER2E1ym0mwDnCHdZwdOwDfxF17VTnBgh7mscPdEscwgistMl1,yYhxvc1cjMVjTp2B984Q9qDYNkHZ66GZd6kW9f5XqV21Da9aV8LhOdznDnAT5F1q6TtAzQT6rWU6EdRdA8IJF2uBIZLT44esM7Ws0dLfgqLdDlUKfXPbzHJEsMvGLVWUPz9WXfi42Ks4FHSO0JRGcPac28tj8XT20dX5omHWmD3PLKj31zDlPn12CiYJqvDa6CGsqi0P01JFRzfKH3chNwL2CeDpyk4IRMaY5zmiCzwpTC9zeFdKnkkHqlVKCWVP,TxsLKe0y7ruquRZrybetl16LWb8ZI23XuGwASZRky7gJgvYNbc3RLPlGIBq9mWNC4XQv24XIl6qfhE09XY2mmzCZ46MXYy3IKPwtHPcuMGEqWHzB880i1z0v6pC7fxwLUstGBWZnCzQ09HfaxHZ4Zuv6Y2Msag8nNuRWKMXwVzMjE6T3Z5dykAC5ziKvJDZyp7FKKJ1Yjr6vDPP8NqKQNHodEDtNBpADw9BjD1MB6pQ2jkBCgS3eCs1FVKqOX8Pp,essMK0XDhFBcFqBZ261wL88jVWdnCTMpxGEEWtCFNfsRBCrQaRH3tFvm4BToolNGHEoZDrq4t3BrKPpo2PcA6EVlQI1wP5Kei5BbUyWiwBV4FwlBOGaG9iIfVEZxXNKEG42aqt5SQEPXb7reziDuZz2C9DiWnLGRra8nBXms5q3GUKiixvf54NkpV2IApc1eBHF5nwL40sPxLejnu7MbUNUmVJz6ColRQWyu41HmK5Clc6KJPGxki403FGrPWu2v,0UIOM5jiHgqrnE6YNWqraRqitgQmkZmw6tAUaaj4r2wCDkZtAyI8IXtFjMuzYv6Hp60j2sJQZGDPpaR1B3Ao9O0YAOuW5LoQRx9NHmq7fAC6meV6h4RAajjPKsMCQqld1VS9rGFQU4qemJmFV5HvnxQj4eyB6Q0zEZyI1DG69CQyv5Rvb3Z4cc1HZXP9iQSzGeagPjRBkuRmfmuniWmcIfz6q3PvSKKPgCqCmxVPEYPNReoo5jiEyysjrV2Jqb6e,L8JyEzTsK6LgMmXXi8mhJZN2QezvJUWZ3rWNO3VrVx0m4Wrf6PNXRnQPDFKzmVxSqaOgen68V7Z5Uob7HjZxzj1svtQ2N6h8cuMZ3WWiJdsn23j22bqvSRSnm6L1klPJeoRDj4C7hsdQZuXoyFaNODfsEHcUEmbk5jdmlmm7EG3SliLzUrOEVyxLAzmYf4hqM4XPKaEkBi1Yg3xa2RGwZFBEVwpXuw510Gm4Lw2byQuOk5ord8G0faBrENtjMf6E,RA3rHNvUfzzeiPGzK3a5712epTtmN7pstUC4zrUpbAXhDj2oXWr1mJwdcfmC7AtwaeynzFtDOsQqXPp9zvEFVrMANtSDIu5f0qmPca0Ewz9buMLf8zyjY8DaPrQF1w1oEQT0TRYeCT7QBYWtjIj6F9VrhNgN6JGirfkQT1nuQxUhKRIcqOdBxOTECTwzDoaEVdHpFLuXXsTwLnl0Kw9WlCXAPgRhifb8HdlEv48KMYGEkpn8eU4nCfkyIWUzPIbP,ppzdsirJxj92bsge3MuLkLwMVsJh4rWJaKnidDYLiF5dcbLWeRMzwzwsZ6bucr3asDTTcPV0v2s23fcCzi7bRWq3dQRzUF78JxJ9Ymxtnky7KY8CsdP5MVi4vvIZpaEbDNoysvM2X7KUdGU8UdFQ5gEv8ibO3fuSEFo6S0ois0lPtm8R6GbYd8ssmMRqngjYDPfBIUvkOYuMHR7oNnUtV22vQX4ytYQZTJId70SvFUZ00F2InPe0N7yr2BjIXzx8,BKuNIHc96DPxrWxPNZNaPJ33ANaAapfAxemxBBvBb6b4kEYmMTDiONmk4zrAbunF7Vujh6sqL4I0qZC5bHUjt0UQtWSS8CpyirLhhkIgQ9MAD8rvgjMTfmowB98uSCTmEODMQvo477iXrfLdaUurJCLaElPCBiZ9gvS6wGdcVVHfHkNODadyZMEqxvafiU77g5jn1iAnn3XVHAiv473DIlaNKGRGG2Uld1R0pEoiUvMOwjhO4AhVORJLxFJ6NMaN,t9VpEoGLUQM2eiVB9p47m79Pd49sRIWLwQOKgAwb1YbMobSTADrjgtzPfVpiqxZYFHifJK9ltXqf83PnaCkYWpbxwEjwXmlTyEG4UJWzLLSIFfr7AEvdvkUUOIqI75Ee4ISMahuJqIb6oWHatIEpM65rJrai30LCpXxEwdteWORHzUcp4oL3np5iGMDEEhh93JbKJ0piG9hCMV1fqhPLac7TlCpjGuC0ygGwUGJTJDxPlVZbcFamYAKUpHrftpTx,UsljuSlV9wVbQdlB8FSOzWOrdX012wHz2vsAYYhD5d73UxyjmqGlQhCJfDfHVeDPiBUTJdLuRnK8HaNoJkM1J3VfyVuOgfuRvf9f4oM1n5FWJW4Pf2GrTBiUlDHCo3gytgZrywRPeBSePT4biI0P7x6QzlP56NnNkS3aLsoc4SPaK03g0hcq8RI58PNmIVvlxKRJ6vXJA2O8IeoFQMJK7XcfplO1QVg00C8n9EO93ePT3ZNRqA0HLQe7J3syLBA7,rIFjUjm39gLJMchEaO3NGtLCsuU8d4el4QJJnqe3ne5tDfb5ouLS9jSxGfh6mT7O4lPFrX9vkovWTJNqSWD8K09ULiJCjU35ac9N62Gv6wpQm9kEs5A5OWo2FUgnxu3aa23vBL33kbsuH2USonGMAihm5Ne6YFR287ZMKve9zDhESf6qF2XCrWyixmLEahvHcc0CAKEqdCVrtpMUhXZrwRWHQSLk570fILFJGb93kJuILtPRlZHFqhgGzuep2B9W,zpOzvJbYOxBXL0PmH1x2Y0t369q8lVBDYEicsaiazoPnM300Djq1cg8SjTI92CvZhbXfdbBuisdFMle7cSEaNxlIenn4wFZqM81uT6w6eVFfERnWsaQ29hYWn2qVuB9RQPd0tMM2ltRAAPke7CeSNhwIJOdrUvSglYDASXW0DDPS28VR6zFQMkVj7w9JRkUVVvpfDfcJ0TJStXkgWGsGMifClD4sbxpy2T4iWNGJw3D6cyCCwL3mKtCqkk1On4D3,hDel025VdLwpuuHNJSypPu4foWe7EEqapknrow2gngjwDTBq7utW7dgPYlNRDlLgr5TDTuW3d2UqfVIv5UDgMYWJOEp4HiJKEtLbQz6LAZnopNPVwsrmUOelrgUf4I1i2wPcrtT2vLNxAS3K8ae6MchE2X7FdEXoVi05PqTGvT1ldlJ3T7umHQqTqZZG2nmi04NCmHL7m5NrrQLmF4SAn1rpXpXKuP9OYCa2Eo7tY7Dnu6nEubNa4Qj8gK1u6RYc,AVDz9osQq1PwjGn1I8VV0Uq8oFCKfpzCUMf0VWXk2ak3yUNqcc6qTaTFpKLBHjNk1rfGDvmmkR0IM2Pcw7mgje7CKQfgjVwdPOzOJL79EApbJSfgrJl3N2tNoh8supH6GK6SaoAGYhX3LYRAKDWnmXUJBLarpagIfkb6mFidrwbqchU63YErJKSp6wiFXPmlffIeL1wVG5dvtHV9InYnPC915JTmZIHit5XURBqndwKP0WlYBGg4BilzAfdZ1GLP,3Q8cG4KxqUTqQ4AKb9WpTiraukESYSLy4LEhGjXIUHlEkDqs09ztF0rDUi2xeok2hgfOdQnqY3VSjG4rdH38uuQU64p1nEQtMyTglt7m331cJKPHxpHAPOx0XohswGM7AOBee2tXJ6fvkoIA1kN7JgjRtbYSVrfWfYtxChS6EEA2UI11B7FHODf2gkw4MaX9MuyIefc1pvDa7wY4enlJfNmuQrao33UeyGsN8UaMB7XkgqQwCXyYphPdfVGSWsiq,9dHzV1KaiQocUC1HwFusNzfvRhT49ZrVy8QodJevwMdvccS2grenN81Oi4xIproaUUqUApKKubMZJAkZDbBl2HWsoKqlIaMUsGErYW3IRMXnFCN976NeoebduBiHtoG6HyV6c32txHNRIItzNOIiZmOPJCcV6eN4urQGdBnRqUIL6y3mJ8Kjpc8WlFRhWaVfjc1zRMOwqu4zrImnvtvYm3VbvE550ZXqsOg7xPkEWr8CWZiPDRvyMbqU1YLVJ9ud,NhhP8HXc1kS2wFBlYhfDSXctInk3FSepfBdEtOqkWOY0uIL5LchnhfSSohkwX1RFeoPJyPTW6W6uaGSPvsBJerZAhYSfy9HdRAfnd9f8zfuoexpc2P0UkyJPpIzDv2pOFk2tPf7kpC2XwdPTCD83dMdTSbB6NghTDsG5lvieutL4GM4OY4sUysdY7KLPno2Rax2lz8Cl1YcaAtzpoIxLveg3YAXtzfz6VeE3Q8vOqdnqP4Xd1s4knQlfWtsKnKup,8TgM6tLeaoBKrtxCZZ2nRcgYc0EigUHKsdY4F569FvI3cRKr52bzJqMUYyK3NUqvEbp0Sy6YlPXDT3XWpb0ehtPZXWMBGQs63tJ69Rn3Ivvn8PTMbh9e2hpMM3hZlBjJaIb8KcaGnNkIAcQpOVwnt8i0lic9wVUChpQNPuNtduWH6tENNwBkBEyYOMoxKOiYIRNROgo4lVcjNrDeS9On0N0ZzCOkK3wYFVZ5kRjxvAGLWNDCSt0aq7UxskLYu4jo,Z1I1inPNuyrEOImkq08yPuhC9avA7dthau2BLAUUpAfQdCEmDs9ooA0lgRgxPhuNYlstD9enC0pUmoxILcHAtWh5xCtXCz0U8xRBQE7LEzyd32Y5M7rzrRMTyiVdkDLzouYi9ASFnohzP4GnixRrpHYqjUier6aGjjP6SrBq5ygXwwL6opBstsNZIX5TUQ5G8wJO36R5Btb8tvuhp98PHW41v5LGwlagCFj7NbsQ60cIBWtUDyGUsXHDjTm2vMCd,EzhGXqulRsreoGQ8uig3RUhcw7k2vGGzyeHM00TSITgiJaZNUkMxNvknxPYixNG2UQDJyP9V3EcDMgxArtUuOnoBTXkOJE9yecuy6G25FXI8moQeH4HTAjgpShP62GnmAesd00NQCv0yWzcFNeHkpjaWKNEQmWPAdr2cUIaqOXS7ES2A9oTa4Aj4vsbbDmkdEyzNU5AZS0VYsVW34HDUX8cdmw2Fsjy6AZLCMM000Ow0j9ANhFi9SL6TLlh494Vz,pflMfP1nHd6h1wcNWeqMxtMimjSQI643PmSfGlt3BK9d6x6nLIuTQkd1x6EyVAY5TLnVclHuqxrA4pjFrTlw2Af5bc0AVXy0EbqawE2eXss8KP9URHupLi53vbONu9jB5Wvdl84sIIwlbNyJaprm80YHjpTFDHf0UAtlrYizotkZ48Wp9cfW9Z1gFOdaLKfWWddqlezna3ahGTZmN5HDOWorUR5Tu54jlqqv63L3wQIJ2HBymHXjwKFsXhoCy5XA,1nImR3wfnm0sPiARSN8SSiRaFj6aVmjxaBtqk5lCpLu3O10vWIACASPlPVb4tjhFXpo83cHxSEYYq4H29pw92PMETiMLFjWLbsbGl3GmxQJE7Mm7xHfrYovMpfo1MFgPfMR636H05kSohyw4FrqewwKoSj4CaEo4X7wTyZjG9kwyg6g2v3AcF9rC9Pyl5Wmh9AZXC6fclIZS8VRIrKx97qURaziDASV6orXsfOBnZuHAyNHMTwAfSm73eHD7ZbNq,rV2QBsnlMutyv1T08sCuYutNxpR9NiBiQYxffpVLpx5Fr4J6i0a3lx9EDB8ceXhrIqX1pV7tlc8xfHz7vumEMWIM0v5jQvOrafMZqp8OTNhLhSFX93mKeXg6CKSxlUoZcqfC22IuJdjn844v26kKIXKTgMQptVcnhlvGCfG5jutbPvuDxtpW7en1GnDTNJpdyB74I0eaCF2BAY6B8EAoYn9II8UbBEkUOm1XDcq5zWiN5R9orx6bU9WbcamJm4Ou,PNeeVijBwz8anmE7hUkMSRvHPqBFJsZhbhLYGOvnRlHzbuJh4TNT0wzFNjzbRTE10Jsu1HW9MZvYCBK0PD2B75NO66twKeq0BYy4upewkp8ZElkBaGZh3LoLvYWWLflmWYqeTXeEgps94jD6fnv6LlEwBB4SCgTEKf4lrWXIgj1rBa0gDnMloDlSA5WN3bHvqBlDzTjhkMaH6JAk2J0RuT24OUC6ptTAjhdb3a72fJ4RmqL02gXCbxwtwxwViVA1,LnfezNiVh6CO4yP3PzQvdY26ufb6PgIRM6jAEG1pHeatPTCzldxyhHpglmYuFCx5Cs6aZcWpjRxhAKcMQdg0docc8RRirc24y1lpGdEgqFTInNmdib9l7m4MfBFfkDvwL4UqfJulPukcn076BxTSmlLS5ng2LE8YMLjmt3lEu7yBu4eTrQ2P3l8iFH86imc99wwhjoQ3AFYwPLOSuvOCtByXBnTr7xBXBSuXXK7uC5dA561mQeKrrgYHQu8BakcT,3OcGUAu9HZq2C4tsufPyFxAyHnpSHd4v3T9sVPXU7chE3pahfuo1qCvLOlCfBAyat1sHst61uXRObx6a0B7tHb5GyzNgAsfr4aNmGEsakNJTqiRePb3frr5snyjb5M7Cf707SSGlOxTFOw3LRrjr0nU5d0Hd4rGtW4L6zD0UPWckPNVwWBnvr1C5SZJtKjtqBncRgi72lzJjGOHKeRbBTYnHoIZbCwMl5vefYj0XzQnYT0bSXdPGmlQ7RfAr6SEk,H49Wgg2jP4JPnx7ySHDJywYdDACnY3Ynh9QlAkeuiuKb6YUb5xObx0phTCSPlk9GmVoxeNTbU4QMSU5qK3ZOrmGyLFijRPsXSZvItOfGNEgHGpwmxb4clrOm2RjVEXlXmo8elemAL0C9zuoB76uxpQ154WIvxD3o9mDQnLT0IBdCVIyYguWhYTnk11WZCKOa2tSswVVX2hVJ2j3Qbtzy5EdzeAo5TTFA4vMMpgVXRUcysPlCAfWIOLN55icXYvdR,To6i4y5uRxkSVwRltNz0HqGtw2iYIZmFnNYMmAhSs23pPB1lSZrCFMwGIiYU2jr7GnuPkLXoknVXor5DOM0FP7N007AzouLgkFxknrthU0b3btLIKoOAVhozhetFhHn5KYr7xhl1KXMuLBkdCkZC3ecNpRseGbHmuAfBJz7kuPhSz3tD4C5OLGf5PYB9oLUNS6Lv4eF7WlW4L29poNbMNjJ4ikMg7o2HSSSXhYNXfBXJm3JaPsHgNhSEb9zvYmf6,0LxDaQC0iTLmYNHM9FLHA3o7HLK0NZPd9rtvObElEAmUK8XObQcvNefPqVUXDxxUVHH5aeamuFCc4lDiqvd4mlgmBePMpPnTgTwW5O1Us8OESZ7yMHpkRjMIQvz4IJUHUfkx6FFjOBOai5kFtY8SgYkX9HpnCWoKKx8dePllS0lmuRsXvZufzQR47y5NieQBdEGFmgAwXruLMNc3ojgmCobqLV7hmkoEq7piyfwkMjwTDnS874ErNlnP7ibJE6dK,BXJzWbSjkeUpo5Bk6uAKwBysAjvBsYEttVbR0dQZ3DMZQZsGgiMFGJBHuheRDQPbzULf78qiQxFDFZqgnssM7otxQvkSqlGrQljoO4PgvVIzk6lIAEIIN7EZUp1l5nywZ7bxzXJi9liogtmLBrAjzTCCk2zPuZJ5a1bQnF3O7mLF83obxypOHTlvqqm0eS7pQcprVYnBpl9vxjcshU2b1mBAD3sXoiJDi2KjtpR7EsTluSqHclMzuCywV12Yc9HZ,ZaY5vA5fvsVLvOjhK74VgIZw1wlT6vPwCnTG1iDiQi3Xzb3m2cO6bw9auLdwmENILzu8ZP1wWRhsisbNU4WW5UixVjVDchRCektd5rCcpcRUpcqbrWAojPh8Yut0nhPWVHosbtFNZVJZmPmuaqZuPD6Yg5yiCwwMV8nINxVsVInRA07TdERgTbEQ6ALch7dYrYH3gCUubL7CwFkgkCtFZyAZHysftTtKlbeDSbGmTFFu6KCkYwAX7M4RA2QbObzO,BAlj0fh4DQqa3EXmxrM8RNJRiylyLxZ3AkdyQmxW8NbXKBNsb4Odxn5KQq2urBMQviqBvIW3r80tImTCaTQHkRdfS1OjGeWrCdvnBZtC3RZPtfja7ySoEgaY7rbrrrIZX39AKQvsBc6XNd40bD3DpKtt0BuTGnznWmvq1SJQjziACZgHsRAAA9GlYcjd5iiXWL9ymnkS43TKiicoUISiKv6LeoXVRNszbcoYz2gB7px2mc52knVz2UxlPNEG5m1K,NYDU4ushhhhFqBKWplZfxnX2YwdIG6zfoygXqONqHudUHlPDvf4MzHSEfRUtJUbpfvtzVKoxyrmGSPSfaArdwK2LYEWc7cFOI8jKZEFbk7QU0NY1a0eKXvbCrU5vISPrD2IAR83uVmhINcSBkX46JrqPHS9Yo0rFpbzFckuNCgObvho8oSUQ5gKOOPRA9Hv7uJjhkreVpKH6R1RFWcHkpv05itMC9yM0NgYCkkFgBmf27yU9UmVjP0kfV9TgfyJf,Gsxq2T6rrWNyWz3fYxLOlypsRTfbjnUWdE63336cPIrEubU08KXKrCJR8rYWYHdgWRcEsCWbS4OWTbYw82Z05iRStb17I0wv3HLLY8sEJX3xNWU4L5kpVNj0nuDRfbDWtUeq81rQATZKtWbgrurPw9oGNMeS1EQ9xPWYo29LKkOvRRSqp3TnA7XSnsHhHWW0Y8IOVfQl7FFijulIWYXl5gKbuDSB5FMbXlOrerPbDy6YeHnfVibV77ZKdvomRrnN,iAARHUw9B2wmCQQTCkw3mmme5Lk70x4RR7VMA1BkoheiyTp3TDODAjp0QldqOsksocoMQey8jjIckCz5Mf2h7srx6Xz1N7zzArZGui82vYoyE9BdCgX75B5SkmC9Z2ize4Fz7lNYqi8NPHmryALYx3DCt6IP8j6Gcvf2G4qay4FQ6cSOl09h4MzwfE744MViIsV4ZtkcOqHb9XoTeSTukdpz2FtRgh6lVvZoS3yVArODDWydm4b1rUxGORN9hl1o,QEOd8jUjVXnJyYl2PfRpQKkXrGtJhIE9OymHY9yCSR9O4OpQS5yQZI8rAU9kTvk6mOqoitHYCSTkjNoe8e55K70C8w9dTtvbVxqvthxRmPOO7viaCEIRrcW33Nz3M6YlGT9GumSOB7L1L23k1Dg7rdVm7keNf65kJBOZtra2M7pJqXBOjsk20xYFGsw3FpyXoMms1GdhjzhQ7AzPpgmILh477fejW1m8wNoFPimmUgSyTr0LZ1qGnkrrbXWw9fL5,EhByNYQGiSI0UmTBbVmZEPSUBb7h9quGl9zXgS88gPq6cSPM3n6vJ2iXKjj54uue79zALmAbHQn1nb9C6qMCULLqYOJSeRBE0uFw18LRC1yAxV8E9eTlBL7gXzJF8XTnB5k0iBkpYzJhNWbyHfOt3S1vjMWc2vJbGeTRSOwwISPOQIOhLOxAQb6vZDwE77R7tT7dCM138VBdGYxIKsfSd61E1X4hwigHzGOC4pSeBDi7W4icDOFaW9FxgsM8KyQt,4a0t0MRxGrHSYjXBwrw8xJ9Qas1alsyqRh6WWhrHFKeEjLGBQ4OPM5GQZvedQ3EZHLF6sez6Z7AMosTy7IY6VESM1tJ0R3F8EWGp3FRt65THSOuqUFRcnsEJvXoxZ81Zp3Z49FRM16wLAhzxUaNSDioNK3a1j8AE7R0xdZVnDvXCMoiGFZtKZlsKsE7VI8eI7E0e0Fy7h0Gt4B7D0EhXw8SavbO4sYojXLJWoZEAOfllF50Y5KJyOGaGzDa3jRh3,UxCCdmUgnXzNvoIJ6FUOHXIgCpgsaRtMYjkg4LJg7VeQELFfzDqDNKjxZUXrUWcC2VwKcP2SAPbArt0elCb15L5A0oC1sulaklWVicbmMr5DHi5FVh6U6KZNrBFBUw722tSsLNXkaqYErOZ4KmTrlRAdcyiRE0KCDtQC4wHO1h1OdhHdlx3JghhL2tWmBYXmVAvDrie5TjXeRSn3hHDicfsk89yVHnz2LRvWuCx4i8GfuhAX9OHrtTtRat89Ksql,MmhxiZRgR9HeDUwWcJEWb9qrDWgTK3275vRZ1c5gpwqZecthgKDYofiAH1AoTh2JZ9axZ3b839PxFOKwkpkzGK3S2Tankhu35W2bwBjmf7JiX47zeNIkolUoon2ADcwuAXipWYyKxwuXkQZ7ZAM2I4nPLTqazKySmmQybVrFRRtNUFZksJ9q0s6AL0bVLJ6vSFxjm11NLVnP3OkRCFwlsPwxwyAhfywVIjBYwgfDiSYKgNECGQQ4hXdFc1Du4SEt,tpGr1Ni5laEoPzVtSV0GmU5krdAz6tpm7X8skTsptmo32LuC4uv1PnoDXwlrMRqIwf6BZwZRpzmBfT4WRAwhih1rZHxFIXMvVzOlI8rwSiCgZN14q4UGAozmjGUR8eR7GF9Pd8CDhrFQ7mdsgkL3tlkewBVP4IwPifqI9RoyAXQketSg9kIzTguYbQ5QwNQ1aP0uhxPf40lqJne3TBEjzwnKuFoBepMZnzzPEshbL8WvRg2wNXB8B4yvkmy7Z4Gr,DF1zfEkn7lkTJOhf022rrcnGZwGfhMitu8T7FUNfNOOdgRSdFdWMiuhw0VCa9jdEL7WRdCmoVF5POZ'
2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [2, 3, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 06:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:51:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC
,[ThaliCore] Session.session(_:peer:didChange:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3720624C-71F8-4A6E-A942-2A1B9013449F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59810
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0c5PJ3eNWBcDmV9igtSWmMP5QRGUhBXV","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DDB824D4-3059-4E09-9390-F930EC2281D6
[ThaliCore] Browser.startListening
2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-24 06:51:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8F45B80A-27AD-4221-BC31-4CA963D9A182
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Session.deinit peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109
[ThaliCore] Session.deinit peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
2017-07-24 06:51:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}]'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
2017-07-24 06:51:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","generation":0}]'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","generation":0}'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B8E3465-C24B-4093-8FE5-81825C4AFE05:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B8E3465-C24B-4093-8FE5-81825C4AFE05", generation: 0)
2017-07-24 06:51:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2B8E3465-C24B-4093-8FE5-81825C4AFE05","generation":0}]'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2B8E3465-C24B-4093-8FE5-81825C4AFE05","generation":0}'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8F45B80A-27AD-4221-BC31-4,CA963D9A182
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F6C0773-8281-4E47-85D1-4F47E19BF28C
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A33C677E-63D5-4B5C-B1F5-C4B4A060DE79", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A33C677E-63D5-4B5C-B1F5-C4B4A060DE79
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A33C677E-63D5-4B5C-B1F5-C4B4A060DE79
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 06:51:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-24 06:51:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-24 06:51:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:f8cf44db-e734-43b9-bcf2-6d7e652024fc error: startListeningNotActive
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JHDRSO7ToxU1l5OcfNlokmJE18ZV68ei","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"f8cf44db-e734-43b9-bcf2-6d7e652024fc","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"f8cf44db-e734-43b9-bcf2-6d7e652024fc","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DD665BC9-5266-424D-94B1-881D3C00E0C3
[ThaliCore] Browser.startListening
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"clgUBn4DYrI5yQ8SR4pnEtAJ37W5fwuq","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-24 06:51:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B8DA7574-37C6-421D-BC17-73FAD9DFEEAB
,[ThaliCore] Browser.startListening
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
2017-07-24 06:51:48 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}},)'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}]'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:4677c3ed-8f1e-428b-b363-085dd74fbf02
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD
2017-07-24 0,6:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6
[ThaliCore] Browser.startListening
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:51:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A5DE92B9-1719-42EA-9D2C-43F8A760B4D1 (syncValue: GWE7HP1BwWubyYxfpEwZUeBZ0Lg5q80a)'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
2017-07-24 06:51:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","generation":0}'
2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
2017-07-24 06:51:52 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59D3765A-2BC9-445D-A1CD-A98041FFB854","generation":0}'
2017-07-24 06:51:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:52 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:51:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A5,DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A5,DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1
[ThaliCore] Advertiser: session connected Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A5,DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:51:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GWE7HP1BwWubyYxfpEwZUeBZ0Lg5q80a","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:51:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GWE7HP1BwWubyYxfpEwZUeBZ0Lg5q80a', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:51:58 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:51:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 06:51:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 06:51:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:51:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1A69943E-B08F-49FD-A918-3969D49A99E8 (syncValue: xtfwLlJjDCDu9VeZhGTRnWN,hRftWtShi)'
2017-07-24 06:51:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A69943E-B08F-49FD-A918-3969D,49A99E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:51:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A
[ThaliCore] Advertiser: session connected Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1
,[ThaliCore] Session.session(_:peer:didChange:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1
[ThaliCore] Session.startOutputStream(with:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 3, 6, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59826
,2017-07-24 06:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xtfwLlJjDCDu9VeZhGTRnWNhRftWtShi","error":null,"portNumber":59826}'
,2017-07-24 06:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xtfwLlJjDCDu9VeZhGTRnWNhRftWtShi', error: 'null', listeningPort: '59826''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) found active relay
,2017-07-24 06:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0rkYNZzs34ZEHqaTKZR1jnCQm0U04Igv","error":null,"portNumber":59826}'
,ok 144 No error
ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) found active relay
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
2017-07-24 06:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3TkdR0T9I6mi8MILb30Z2fYOZ1cr02cS","error":null,"portNumber":59826}'
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 3, 6, 10, 11]
,ok 147 No error
,ok 148 Ports equal
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A
,[ThaliCore] Session.startOutputStream(with:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 3, 6, 10, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:,) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[Th,aliCore] VirtualSocket.deinit vsID:12 [2, 3, 6, 10, 11]
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 06:52:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vs,ID:10
2017-07-24 06:52:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskI,dToSecret":null,"networkType":null}})'
,2017-07-24 06:52:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] VirtualSocket.deinit vsID:10 [2, 3, 6, 11]
[ThaliCore] Advertiser.stopAdvertising() peerID:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1A69943E-B08F-49FD-A918-3969D49A99E8
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59826
[ThaliCore] VirtualSocket.closeStr,eams() vsID:11
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] Session.disconnect() peer:1A69943E-B08F-49FD-,A918-3969D49A99E8:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:11 [2, 3, 6]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1 state: connected -> notConnected
[T,haliCore] Advertiser: session notConnected Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xtfwLlJjDCDu9VeZhGTRnWNhRftWtShi","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A
,[ThaliCore] Session.deinit peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-24 06:52:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 06:52:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-24 06:52:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 06:52:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:07 - DEBUG createNativeListener: 'listening 59830'
,ok 149 Should throw
,# teardown
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 59832'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 59835'
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
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 59839'
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
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 59844'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 59848'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 59852'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'listening 59856'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'listening 59860'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
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
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
,2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'listening 59912'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 06:52:12 - DEBUG createNativeListener: 'listening 59916'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 59919'
ok 196 port must be in range
,# teardown
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 59920'
,ok 197 second start should return same port
,# teardown
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 59922'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-24 06:52:14 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 06:52:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 59925
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:577FB140-91A3-4526-AC67-8110F8393314:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","generation":0}'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1A69943E-B08F-49FD-A918-3969D49A99E8 (syncValue: PhAGhnbdFSr0NBDR0f2dH8QgFeTga6ik)'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59D3765A-2BC9-445D-A1CD-A98041FFB854","generation":0}'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","generation":0}'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58BABA89-9A63-45D3-9381-F655C03EFBAA","generation":0}'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8
[ThaliCore] Advertiser: session connected Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(d,idReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8 state: notConnected -> connecting
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:52:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PhAGhnbdFSr0NBDR0f2dH8QgFeTga6ik","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:52:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PhAGhnbdFSr0NBDR0f2dH8QgFeTga6ik', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:52:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:52:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 06:52:23 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:52:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 577FB140-91A3-4526-AC67-8110F8393314 (syncValue: BqQcHMboS3c2dYDeIgZ8v6K,OIcxxaTIM)'
2017-07-24 06:52:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F,8393314:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:52:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
2017-07-24 06:52:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","generation":0}'
,2017-07-24 06:52:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59935
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BqQcHMboS3c2dYDeIgZ8v6KOIcxxaTIM","error":null,"portNumber":59935}'
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BqQcHMboS3c2dYDeIgZ8v6KOIcxxaTIM', error: 'null', listeningPort: '59935''
,ok 210 should be equal
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58BABA89-9A63-45D3-9381-F655C03EFBAA (syncValue: y23xpYCup01fVZzVbnUOMdYrl3Mo3QKt)'
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2
[ThaliCore] Advertiser: session connected Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59938
,2017-07-24 06:52:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y23xpYCup01fVZzVbnUOMdYrl3Mo3QKt","error":null,"portNumber":59938}'
,2017-07-24 06:52:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'y23xpYCup01fVZzVbnUOMdYrl3Mo3QKt', error: 'null', listeningPort: '59938''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:52:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2A8E8C04-7FDF-475E-B232-F,97B78C2F1BC
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:577FB140-91A3-4526-AC67-8110F8393314
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59935
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:577FB140-91A3-4526-AC67-8110F8393314:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:58BABA89-9A63-45D3-9381-F655C03EFBAA
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59938
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
,2017-07-24 06:52:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BqQcHMboS3c2dYDeIgZ8v6KOIcxxaTIM","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y23xpYCup01fVZzVbnUOMdYrl3Mo3QKt","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"58BABA89-9A63-45D3-9381-F655C03EFBAA","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"58BABA89-9A63-45D3-9381-F655C03EFBAA","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
,[ThaliCore] Session.deinit peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 59940
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24, 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8E536049-181F-4A81-B849-449127FF5604
2017-07-24 0,6:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
[ThaliCore] Browser.startListening
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
2017-07-24 06:52:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","generation":0}'
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 577FB140-91A3-4526-AC67-8110F8393314, (syncValue: ldYDJqUDR7vXfaYRdg83sMcn3bYhoXhR)'
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F83,93314", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
2017-07-24 06:52:32, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58BABA89-9A63-45D3-9381-F655C03EFBAA","generation":0}'
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:32 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,7FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,77FB140-91A3-4526-AC67-8110F8393314", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,7FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
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
[ThaliCore] Session.disconnect() peer:57,7FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,77FB140-91A3-4526-AC67-8110F8393314", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F
[ThaliCore] Advertiser: session connected Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,7FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:577FB140,-91A3-4526-AC67-8110F8393314 error: max retries exceeded
2017-07-24 06:52:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ldYDJqUDR7vXfaYRdg83sMcn3bYhoXhR","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:52:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ldYDJqUDR7vXfaYRdg83sMcn3bYhoXhR', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:52:43 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-24 06:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-24 06:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:52:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ABB6C619-722B-4372-96F0-259A80A2AF24 (syncValue: fCmjnny,OANFxnMEUBEIcvGCGqBifuTBA)'
,2017-07-24 06:52:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-24 06:52:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F
,[ThaliCore] Session.session(_:peer:didChange:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001
[ThaliCore] Advertiser: session connected Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59957
2017-07-24 06:52:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fCmjnnyOANFxnMEUBEIcvGCGqBifuTBA","error":null,"portNumber":59957}'
2017-07-24 06:52:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fCmjnnyOANFxnMEUBEIcvGCGqBifuTBA', error: 'null', listeningPort: '59957''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-07-24 06:52:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2909281D-1594-4825-9D81-6E148BA659E3 (syncValue: YqFNEB5qE1sQIUNGBMCdLh7cHjpOdWjs)'
2017-07-24 06:52:,46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "29,09281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59963
2017-07-24 06:52:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YqFNEB5qE1sQIUNGBMCdLh7cHjpOdWjs","error":null,"portNumber":59963}'
,2017-07-24 06:52:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YqFNEB5qE1sQIUNGBMCdLh7cHjpOdWjs', error: 'null', listeningPort: '59963''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:52:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8E536049-181F-4A81-B849-449127FF5604
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:59963
[ThaliCore] Session.disconnect() peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:ABB6C619-722B-4372-96F0-259A80A2AF24
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59957
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001
[ThaliCore] Sessio,n.deinit peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:2909281D-1594-4825-9D81-6E148BA659E3
2017-07-24 06:52:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YqFNEB5qE1sQIUNGBMCdLh7cHjpOdWjs","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 06:52:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'listening 59967'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DDD527D1-8FC4-46D9-BB12-CDB2C2B9A2AD
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 229 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,# teardown
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}]'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}]'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:52:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:52:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 230 must be stopped
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
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'listening 59968'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93F4E9D2-351D-47B1-BAF9-B7D1970FA2F6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:93F4E9D2-351D-47B1-BAF9-B7D1970FA2F6
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93F4E9D2-351D-47B1-BAF9-B7D1970FA2F6", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:93F4E9D2-351D-47B1-BAF9-B7D1970FA2F6
2017-07-24 0,6:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:93F4E9D2-351D-47B1-BAF9-B7D1970FA2F6
,[ThaliCore] Advertiser.stopAdvertising() peerID:93F4E9D2-351D-47B1-BAF9-B7D1970FA2F6
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'listening 59971'
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
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 236 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'listening 59972'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BF0B2ADA-5893-4542-9F53-AF07754F2607
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D159811D-7213-4264-8BE3-7432233EB525", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D159811D-7213-4264-8BE3-7432233EB525
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D159811D-7213-4264-8BE3-7432233EB525
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 242 must be stopped
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
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'listening 59975'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7021EE65-422F-4DBE-825C-36D4069390AC
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9AC7A578-1256-4E57-BCD8-C54E51CE3F05", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9AC7A578-1256-4E57-BCD8-C54E51CE3F05
2017-07-24 0,6:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,# teardown
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}]'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}]'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9AC7A578-1256-4E57-BCD8-C54E51CE3F05
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-24 06:52:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'listening 59977'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:31446476-D8AA-4695-A23F-A53E6789B3B4
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3F7A0342-AE14-4272-88AD-49AFFF6A0300", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3F7A0342-AE14-4272-88AD-49AFFF6A0300
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3F7A0342-AE14-4272-88AD-49AFFF6A0300
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,onTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"net,workType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdverti,sements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-24 06:52:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
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
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-24 06:52:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
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
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
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
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59980'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6EA58E07-504F-480A-8FBC-A56CF32AF004
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 discoveryActive matches
,ok 267 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59981'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4345AB5F-3FA2-4631-9438-CD7F1358C3CA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4345AB5F-3FA2-4631-9438-CD7F1358C3CA
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:4345AB5F-3FA2-4631-9438-CD7F1358C3CA
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59983'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59984'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:58887D6E-0140-4284-804A-B9A9772202C7
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EFA10F47-8E80-410D-B29C-B26447010EDD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EFA10F47-8E80-410D-B29C-B26447010EDD
2017-07-24 0,6:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
2017-07-24 06:53:00 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}]'
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}]'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
2017-07-24 06:53:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}]'
2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 06:53:01 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EFA10F47-8E80-410D-B29C-B26447010EDD
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:53:01 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-07-24 06:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 277 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:53:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-24 06:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-24 06:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,2017-07-24 06:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'listening 59986'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:53:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "57D5CC84-0578-4F84-9A1C-FCC81840B6BB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:57D5CC84-0578-4F84-9A1C-FCC81840B6BB
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:53:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 06:53:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"35007D94-7682-4602-94,7D-7A22EA1AB0AF","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrappe,r[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24",,"generation":0}]'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}]'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}'
2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"pe,erAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 35007D94-7682-4602-947D-7A22EA1AB0AF (syncValue: Zf3g1OAPv27MoZV2LxtHlTNJ5L4828Km)'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57D5CC84-0578-4F84-9A1C-FCC81840B6BB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57D5CC84-0578-4F84-9A1C-FCC81840B6BB", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}]'
2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
,2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 06:53:07 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
2017-07-24 06:53:08 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}]'
2017-07-24 06:53:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}'
,2017-07-24 06:53:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 06:53:08 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:35,007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,5007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:53:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Zf3g1OAPv27MoZV2LxtHlTNJ5L4828Km","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:53:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Zf3g1OAPv27MoZV2LxtHlTNJ5L4828Km', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:53:09 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 06:53:09 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 06:53:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:35007D94-7682-4602-947D-7A22EA1AB0AF
2017-07-24 06:53:09 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
,2017-07-24 06:53:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00 (syncValue: At4ke8XgqsdLWsXEtACOQqIeQsTSZcar)'
,2017-07-24 06:53:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59991
,2017-07-24 06:53:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"At4ke8XgqsdLWsXEtACOQqIeQsTSZcar","error":null,"portNumber":59991}'
2017-07-24 06:53:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'At4ke8XgqsdLWsXEtACOQqIeQsTSZcar', error: 'null', listeningPort: '59991''
,2017-07-24 06:53:12 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 3, 6, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:53:12 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:12 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:57D5CC84-0578-4F84-9A1C-FCC81840B6BB
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-24 06:53:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59991
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] Session.disconnect() peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:13 [2, 3, 6]
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:20 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:53:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-24 06:53:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:21 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
,ok 291 error should be null
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
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'listening 59993'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
,ok 297 error should be null
,ok 298 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
,ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 59994'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:32B927F2-C8E5-40AF-89DE-4542892AE264
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 304 error should be null
,ok 305 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,# teardown
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}]'
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}'
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 59995'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8387B795-26ED-4334-B999-4D2467040C2D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8387B795-26ED-4334-B999-4D2467040C2D
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 311 error should be null
,ok 312 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8387B795-26ED-4334-B999-4D2467040C2D", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:8387B795-26ED-4334-B999-4D2467040C2D
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8387B795-26ED-4334-B999-4D2467040C2D
,[ThaliCore] Advertiser.stopAdvertising() peerID:8387B795-26ED-4334-B999-4D2467040C2D
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 59998'
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
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'listening 59999'
ok 330 first call should succeed
ok 331 first call should succeed
ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 06:53:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c8029bb-ed8e-4a82-ba80-8f2d58d9e36e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 342 should be called once
,ok 343 should not have been called more than once
,# teardown
,2017-07-24 06:53:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6c8029bb-ed8e-4a82-ba80-8f2d58d9e36e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# can get the network status
,ok 347 network status should have certain non-empty properties
,# teardown
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 351 we have not added peer to the cache yet
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5c650dd2-ee09-4eec-9662-d7bb22155a40","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 352 peer should be available
,ok 353 cache contains native peer
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5c650dd2-ee09-4eec-9662-d7bb22155a40","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 354 peer should be unavailable
,ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dca487cb-bf7f-4353-9a01-3a70a0ac95e7","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 360 peer should be available
ok 361 cache contains wifi peer
2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dca487cb-bf7f-4353-9a01-3a70a0ac95e7","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4af29b21-82d4-4f4f-8211-32fe3091bd3b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 367 first peer is available
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2d10c42f-0ba3-49ef-9ce8-3afa89204b9e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 368 second peer is available
,ok 369 first and second peers are different
,# teardown
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4af29b21-82d4-4f4f-8211-32fe3091bd3b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2d10c42f-0ba3-49ef-9ce8-3afa89204b9e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"592b00b6-a4ca-4e70-8964-a33755af0e2e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"592b00b6-a4ca-4e70-8964-a33755af0e2e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e8f6b2bf-8355-4e8f-be87-abfc58f28682","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 384 peer should be available
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e8f6b2bf-8355-4e8f-be87-abfc58f28682","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 385 peer should be available
,ok 386 should store correct generation
,# teardown
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e8f6b2bf-8355-4e8f-be87-abfc58f28682","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
,ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'listening 60000'
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fa6d7e9f-c1ab-4ab4-a332-580504fbf751","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 discovered correct peer
,ok 391 got correct generation
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fa6d7e9f-c1ab-4ab4-a332-580504fbf751","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fa6d7e9f-c1ab-4ab4-a332-580504fbf751","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 60001'
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0e64729c-6b01-4329-8823-985a2cda4071","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 397 discovered available peer
,ok 398 peer is available
,# teardown
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0e64729c-6b01-4329-8823-985a2cda4071","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dab299b3-f605-4d30-8d0d-b0512fb0907f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 402 peer should be ,available
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dab299b3-f605-4d30-8d0d-b0512fb0907f","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 403 peer, should be unavailable
ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 60002'
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"011f21dd-29e2-4894-8ce1-1faf7e3584ee","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 first peer is expected to be available
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51858b5c-3a87-408f-b920-455053a47a59","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 second peer is expected to be available
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"51858b5c-3a87-408f-b920-455053a47a59","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51858b5c-3a87-408f-b920-455053a47a59","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 we found peer again
,ok 413 it was wifi peer
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"51858b5c-3a87-408f-b920-455053a47a59","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"011f21dd-29e2-4894-8ce1-1faf7e3584ee","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
,ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-24 06:53:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
,ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 60003'
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6fb12e99-74c9-4882-9960-4be61dc9249a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 422 first peer is expected to be available
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"141e130d-6c9a-448b-98a2-3a53b9549b12","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 423 second peer is expected to be available
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6fb12e99-74c9-4882-9960-4be61dc9249a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 424 peer became unavailable
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"141e130d-6c9a-448b-98a2-3a53b9549b12","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-24 06:53:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
ok 430 error should be null
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
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21d4116d-870e-4727-ad76-5d021a719ee8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 435 peer discovered first time does not have new address
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21d4116d-870e-4727-ad76-5d021a719ee8","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 436 address has not been changed
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21d4116d-870e-4727-ad76-5d021a719ee8","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 437 new port handled correctly
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21d4116d-870e-4727-ad76-5d021a719ee8","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 438 new host handled correctly
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21d4116d-870e-4727-ad76-5d021a719ee8","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
,ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-24 06:53:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
,ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
,ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-24 06:53:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
,ok 451 error should be null
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
,2017-07-24 06:53:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
,ok 458 error should be null
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
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'listening 60006'
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eaf54624-5e1a-4886-89c3-ec6ef2356f9b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 Got specific error message
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"eaf54624-5e1a-4886-89c3-ec6ef2356f9b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'listening 60007'
2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"910d57aa-6779-4f9e-9c9e-87c17c5d8700","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:910d57aa-6779-4f9e-9c9e-87c17c5d8700
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"910d57aa-6779-4f9e-9c9e-87c17c5d8700","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 60008'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:738821B2-E99C-43DC-AFBC-0D464E2B90B7
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"671d540c-b879-4f37-a4e8-23246c6b189a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"03ce87df-1645-4766-bba9-28e5fd5a642e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"671d540c-b879-4f37-a4e8-23246c6b189a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"03ce87df-1645-4766-bba9-28e5fd5a642e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}]'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}'
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
,2017-07-24 06:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 60009'
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"42b6d9cf-e1d1-4a59-b0c7-8ead86f9abc1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 1
,ok 511 2
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ae6ee121-3332-40f4-96c8-7f85b552baf5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"42b6d9cf-e1d1-4a59-b0c7-8ead86f9abc1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ae6ee121-3332-40f4-96c8-7f85b552baf5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 60010'
,ok 518 error should be null
,ok 519 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2E94013A-F1F3-45ED-A4A4-58C18682083B
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 520 error should be null
ok 521 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 52C68463-0618-4ED7-A9C9-4CE393CD01D3 (syncValue: 0)'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0)
2017-07-24 06:53:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","generation":0}]'
2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E614,02067D","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
2017-07-24 06:53:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,2C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
2017-07-24 06:53:42 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
2017-07-24 06:53:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 06:53:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,2C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 06:53:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:43 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for EF040FDE-0D6B-4D8D-A867-F3E61402067D (syncValue: 1)'
2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
[ThaliCore] Advertiser: session connected Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Advertiser: session connected Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60019
,2017-07-24 06:53:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":60019}'
,2017-07-24 06:53:47 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 2)'
,2017-07-24 06:53:47 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
,[ThaliCore] Session.startOutputStream(with:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [2, 3, 6, 14]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 3, 6, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 3, 6, 14, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:53:47 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:47 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60025
,2017-07-24 06:53:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":60025}'
,[ThaliCore] BrowserManager.disconnect peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 3, 6, 14, 15, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:53:50 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:50 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,2017-07-24 06:53:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2E94013A-F1F3-45ED-A4A4-58C18682083B
,2017-07-24 06:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 06:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" ,UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketD,isconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
ok 525 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErr,orDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 526 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketD,isconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] VirtualSocket.deinit vsID:14 [2, 3, 6, 15, 16, 17]
# set,up
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [2, 3, 6, 15, 17]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[Th,aliCore] VirtualSocket.deinit vsID:15 [2, 3, 6, 17]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketD,isconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] Session.deinit peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[Th,aliCore] VirtualSocket.deinit vsID:17 [2, 3, 6]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisco,nnectHandler
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 06:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
,ok 537 after start
,2017-07-24 06:53:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-24 06:53:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 544 agent's destroy should be called
ok 545 agent's destroy should not be called again
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
ok 569 Entry 2_2 does not exist
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
,ok 615 2nd good enqueue
,ok 616 we are in the pool
,ok 617 We are out of the pool
,ok 618 Action was killed
,ok 619 The original kill was called too
,ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
,ok 622 first kill
,ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
ok 625 2nd good enqueue
ok 626 1st action is in the pool
ok 627 2nd action is in the pool
ok 628 1st action is out of the pool
ok 629 2st action is out of the pool
ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-24 06:54:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
,ok 632 Start should not be called
,ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 06:54:08 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 637 Got null
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 638 is an agent
2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'actio,n returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
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
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 647 should have gotten null
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 648 Should have stopped nicely
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 649 Still looking for null
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
,ok 653 (unnamed assert)
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 654 is an agent
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
,ok 665 First does not throw
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 666 is an agent
,ok 667 Second does not throw
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
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
,ok 682 reject reason should be: Could not establish TCP connection
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
,ok 695 must return null after successful call
,# teardown
,2017-07-24 06:54:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-24 06:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
,ok 697 Should be Could not establish TCP connection
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
ok 741 bluetooth peer's notification has correct connection type
ok 742 tcp peer's notification has correct connection type
2017-07-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 06:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
2017-07-24 06:54:30 - WARN thaliNotificationClient: 'peer is not available'
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
,ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 06:54:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
,# teardown
,2017-07-24 06:54:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
,ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
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
ok 801 should be 204
,# teardown
,2017-07-24 06:54:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-07-24 06:54:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
,# teardown
,2017-07-24 06:54:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
,ok 806 not equal connection type
,ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-24 06:54:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
,2017-07-24 06:54:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
ok 812 first action kill called
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
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
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
,2017-07-24 06:54:56 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:54:57 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:54:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
ok 851 All tests passed!
,# teardown
,2017-07-24 06:54:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-24 06:55:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:55:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:55:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
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
,2017-07-24 06:55:09 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:55:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-24 06:55:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 06:55:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 858 action should be killed
,ok 859 Error should be timed out
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
,ok 863 same localDbName
,ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-24 06:55:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'listening 60152'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] Browser.startListening
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:00404456-957A-4F5F-9043-36855CD19826
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
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}]'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Advertiser: session connected Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D6EAF055-2C60-4762-A755-7A84207314F0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Advertiser: session connected Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60156
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":60156}'
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2C25BD08-82E6-4993-AE40-B3DCC8B04381 (syncValue: 4)'
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 3, 6, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:18 [2, 3, 6]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [2, 3, 6, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:19 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 3, 6, 19, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 3, 6, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 3, 6, 19, 20, 21, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandl,er
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [2, 3, 6, 19, 20, 21, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [2, 3, 6, 19, 20, 21, 23]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 3, 6, 19, 20, 21, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 3, 6, 19, 20, 21, 23]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 3, 6, 19, 20, 21, 23, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [2, 3, 6, 19, 20, 21, 25]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 3, 6, 19, 20, 21, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [2, 3, 6, 19, 20, 21, 26]
,2017-07-24 06:55:20 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D6EAF055-2C60-4762-A755-7A84207314F0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 3, 6, 19, 20, 21, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60169
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":60169}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [2, 3, 6, 19, 20, 21, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 5)'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":60025}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [2, 3, 6, 19, 20, 21, 26, 27, 28, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 3, 6, 19, 20, 21, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [2, 3, 6, 19, 20, 21, 26, 27, 28, 29]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 06:55:21 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 3, 6, 19, 20, 21, 26, 27, 28, 29, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:28 [2, 3, 6, 19, 20, 21, 26, 27, 29, 31]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [2, 3, 6, 19, 20, 21, 26, 29, 31]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 3, 6, 19, 20, 21, 26, 29, 31, 32]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [2, 3, 6, 19, 20, 21, 26, 31, 32]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 6)'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":60025}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33]
,2017-07-24 06:55:21 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 7)'
,2017-07-24 06:55:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
,2017-07-24 06:55:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":60025}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:39 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 06:55:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37, 38, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37, 38, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37, 38, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 3, 6, 19, 20, 21, 26, 31, 32, 33, 35, 36, 37, 38, 40, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [2, 3, 6, 19, 20, 21, 26, 31, 33, 35, 36, 37, 38, 40, 41, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Tha,liCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [2, 3, 6, 19, 20, 21, 26, 33, 35, 36, 37, 38, 40, 41, 42, 43]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [2, 3, 6, 19, 20, 21, 26, 33, 36, 37, 38, 40, 41, 42, 43]
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [2, 3, 6, 19, 20, 21, 26, 33, 36, 37, 38, 41, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 3, 6, 19, 20, 21, 26, 33, 36, 37, 38, 41, 42, 43, 44]
[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.deinit vsID:43 [2, 3, 6, 19, 20, 21, 26, 33, 36, 37, 38, 41, 42, 44]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
,[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 3, 6, 19, 20, 21, 26, 33, 36, 37, 38, 41, 42, 44, 45]
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:36 [2, 3, 6, 19, 20, 21, 26, 33, 37, 38, 41, 42, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client dis,connected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 3, 6, 19, 20, 21, 26, 33, 37, 38, 42, 44, 45]
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [2, 3, 6, 20, 21, 26, 33, 37, 38, 42, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:20 [2, 3, 6, 21, 26, 33, 37, 38, 42, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:26 [2, 3, 6, 21, 33, 37, 38, 42, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:45 [2, 3, 6, 21, 33, 37, 38, 42, 44]
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:33
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:33 [2, 3, 6, 21, 37, 38, 42, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:37 [2, 3, 6, 21, 38, 42, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:38 [2, 3, 6, 21, 42, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [2, 3, 6, 21, 44]
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:00404456-957A-4F5F-9043-36855CD19826
,2017-07-24 06:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:55:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"99E26CE2-0BAD-4BFD-95A2-9934C3008397","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:55:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 06:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [2, 3, 6, 44]
,2017-07-24 06:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:44
[ThaliCore] Virt,ualSocket.closeStreams() vsID:44
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:44 [2, 3, 6]
,ok 865 passed
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:D6EAF055-2C60-4762-A755-7A84207314F0 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] Session.deinit peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] AdvertiserRelay.deinit
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'listening 60188'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
,[ThaliCore] Browser.startListening
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E70E9642-D542-4465-BF,89-DFBB13C20E5E","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","generation":0}'
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00C1C796-5,CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
2017-07-24 0,6:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","generation":0}]'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","generation":0}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E70E9642-D542-4465-BF89-DFBB13C20E5E (syncValue: 8)'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:60169
[ThaliCore] Session.disconnect() peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Session disconnected","portNumber":null}'
2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIde,ntifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
[ThaliCore] Session.session(_:pee,r:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60025
[ThaliCore] Session.dis,connect() peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":true,"generation":0,"portNumber",:null,"recreated":true}'
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:36 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60191
2017-07-24 06:55:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":60191,}'
,2017-07-24 06:55:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 9)'
2017-07-24 06:55:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
[ThaliCore] Advertiser: session connected Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [2, 3, 6, 46]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandl,er state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [2, 3, 6]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [2, 3, 6, 47]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:38 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-24 06:55:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 866 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [2, 3, 6]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] Session.session(_:peer:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:00,C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,0C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] Session.startOutputStream(with:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [2, 3, 6, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [2, 3, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) clie,nt disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] Session.startOutputStream(with:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [2, 3, 6, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:00,C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,0C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,2017-07-24 06:55:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
,2017-07-24 06:55:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
,2017-07-24 06:55:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 06:55:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:43 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:peer:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00,C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 773BB6AC-864D-4771-BE0C-DA3F1B91DBAC (syncValue: 10)'
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "77,3BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:55:45 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] Advertiser: session connected Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60204
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":60204}'
,[ThaliCore] BrowserManager.disconnect peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381
2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 11)'
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871
,2017-07-24 06:55:48 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [2, 3, 6, 49, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [2, 3, 6, 49]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [2, 3, 6, 49, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
,[ThaliCore] Session.session(_:peer:didChange:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6 state: connecting -> connected
,2017-07-24 06:55:48 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-24 06:55:48 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 867 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [2, 3, 6, 49]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] Session.startOutputStream(with:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [2, 3, 6, 49, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [2, 3, 6, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] Session.startOutputStream(with:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,3 [2, 3, 6, 49, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
,[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [2, 3, 6, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1
,2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:55:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:55:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 06:55:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [2, 3, 6]
,2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:55:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:55:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 926 constructor called once
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
,ok 936 start called once
,ok 937 stop called once
,ok 938 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-24 06:55:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-24 06:55:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,ok 967 constructor called once
,ok 968 constructor called with right args
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
,ok 985 Got right error
,# teardown
,2017-07-24 06:56:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-24 06:56:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 986 Got socket hang up
,# teardown
,2017-07-24 06:56:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-24 06:56:05 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 987 Got 500 as expected
,# teardown
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
,ok 995 revs are equal
,ok 996 should be equal
,ok 997 revs are equal
,# teardown
,2017-07-24 06:56:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C4506D9D-,A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-24 06:56:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 998 Our rev is old so we should fail
,# teardown
,2017-07-24 06:56:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 999 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,4506D9D-A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C4506D9D-,A119-4EE9-B5E5-528960C39762/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
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
,2017-07-24 06:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-24 06:56:20 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1005 Expected bad seq error
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
,2017-07-24 06:56:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1013 We waited long enough
,ok 1014 should be equal
,# teardown
,2017-07-24 06:56:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1015 Should have gotten same timer promise
,ok 1016 Still same timer promise
,ok 1017 We waited long enough
,ok 1018 should be equal
,# teardown
,2017-07-24 06:56:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-24 06:56:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:33 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'listening 60279'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EDD1CB16-4491-413B-B088-E15A1100BC47
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D871F145-5C3D-4115-9F1B-512345E333C3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D871F145-5C3D-4115-9F1B-512345E333C3
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-24 06:56:33 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D871F145-5C3D-4115-9F1B-512345E333C3
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1059 ThaliMobile.stop was called once
,ok 1060 ThaliMobile.stop was called with 0 arguments
,ok 1061 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1062 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1063 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1064 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-24 06:56:34 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 60281'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AFCFD3F6-2B45-4562-9A11-95C383D7D20B
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BDF861B4-1826-44B7-BCA8-E7879BA9DF79", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BDF861B4-1826-44B7-BCA8-E7879BA9DF79
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BDF861B4-1826-44B7-BCA8-E7879BA9DF79
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
,ok 1105 ThaliMobile.stop was called once
,ok 1106 ThaliMobile.stop was called with 0 arguments
,ok 1107 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1108 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1109 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1110 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 60283'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A8008D75-BEF4-402F-9424-5B20F7616516
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F165D20C-472A-439A-B436-3600C2BC2EC6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F165D20C-472A-439A-B436-3600C2BC2EC6
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F165D20C-472A-439A-B436-3600C2BC2EC6
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
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 60285'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3291FB72-814A-41F8-A72D-DE5300853FB1
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FA312C8B-B803-4855-902B-9FCB42667BE1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FA312C8B-B803-4855-902B-9FCB42667BE1
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FA312C8B-B803-4855-902B-9FCB42667BE1
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 60287'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1FEF5685-B9BE-479A-8B3B-147AC7973E2F
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "656217D8-AC12-44AF-9684-A64FBB1AC8C6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:656217D8-AC12-44AF-9684-A64FBB1AC8C6
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:656217D8-AC12-44AF-9684-A64FBB1AC8C6
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call ,of onCheckpointReached handler on a single db change'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***T,EST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler ,on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - test defaultAdapter'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
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
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
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
,2017-07-24 06:56:37 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-24 06:56:37 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
