#### Test 113351851fe156cf_iOS_Thali56 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone SE 'Thali56' (8effff55cdeae82604a08043752b940f94063299) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping N69uAP 'Thali55' (d7a40d176e510e468af45ed03d4ca45fd18dbe43).
,(lldb) command source -s 0 '/tmp/05E82A7B-1BE9-49AE-B955-409CE2C3583B/fruitstrap-lldb-prep-cmds-8effff55cdeae82604a08043752b940f94063299'
,Executing commands in '/tmp/05E82A7B-1BE9-49AE-B955-409CE2C3583B/fruitstrap-lldb-prep-cmds-8effff55cdeae82604a08043752b940f94063299'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56760"
,(lldb)     command script import "/tmp/05E82A7B-1BE9-49AE-B955-409CE2C3583B/fruitstrap_8effff55cdeae82604a08043752b940f94063299.py"
,(lldb)     command script add -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.safequit_command safequit
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
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTe,sts.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5433068D-C8C9-47E8-AACA-FAE7D4FBD8AD", generation: 0)
[ThaliCore] Advertiser.st,artAdvertising with peerID:5433068D-C8C9-47E8-AACA-FAE7D4FBD8AD
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8011D487-B595-4C5F-A7CB-5F60EA5B55E3
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:49558609-0D21-472A-83E7-850D1E82812E
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EEE8E073-D353-4B44-93C8-D6E9E8BA3F39", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EEE8E073-D353-4B44-93C8-D6E9E8BA3F39
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EEE8E073-D353-4B44-93C8-D6E9E8BA3F39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EEE8E073-D353-4B44-93C8-D6E9E8BA3F39", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-12 07:46:09 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.938606023788452
,2017-07-12 07:46:09 - DEBUG UnitTest_app: 'My device name is: 'Apple-Thali56''
,2017-07-12 07:46:09 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EEE8E073-D353-4B44-93C8-D6E9E8BA3F39:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EEE8E073-D353-4B44-93C8-D6E9E8BA3F39", generation: 0)
,2017-07-12 07:46:11 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5DE8C992-1D37-4000-9FFE-BC6F0CA43BC8/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-12 07:46:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2017-07-12 07:46:12 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
,2017-07-12 07:47:02 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-07-12 07:47:02 - DEBUG CoordinatedClient: 'test client failed'
2017-07-12 07:47:02 - DEBUG CoordinatedClient: '50000'
,2017-07-12 07:47:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-07-12 07:47:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
