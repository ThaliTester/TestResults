#### Test 113351851fe156cf_iOS_Thali55 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of N69uAP 'Thali55' (d7a40d176e510e468af45ed03d4ca45fd18dbe43) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FC91DA25-14EF-405A-A6FE-3D0ACD661E97/fruitstrap-lldb-prep-cmds-d7a40d176e510e468af45ed03d4ca45fd18dbe43'
,Executing commands in '/tmp/FC91DA25-14EF-405A-A6FE-3D0ACD661E97/fruitstrap-lldb-prep-cmds-d7a40d176e510e468af45ed03d4ca45fd18dbe43'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56758"
,(lldb)     command script import "/tmp/FC91DA25-14EF-405A-A6FE-3D0ACD661E97/fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.py"
,(lldb)     command script add -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.safequit_command safequit
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
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 07:46:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98107EB4-A432-49AE-B023-D526183FAEC2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:98107EB4-A432-49AE-B023-D526183FAEC2
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D232A88D-175B-44E8-B39D-,DE9F98D30D8A
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:46978C27-7740-4488-A8C1-8606B66A1BCA
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C56E8E4F-0182-4B47-AFC0-E3C764A28ACA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C56E8E4F-0182-4B47-AFC0-E3C764A28ACA
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C56E8E4F-0182-4B47-AFC0-E3C764A28ACA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C56E8E4F-0182-4B47-AFC0-E3C764A28ACA", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
2017-07-12 07:46:09 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignor,ed tests:  0
Total duration:  1.584451019763947
2017-07-12 07:46:09 - DEBUG UnitTest_app: 'My device name is: 'Apple-Thali55''
2017-07-12 07:46:09 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C56E8E4F-0182-4B47-AFC0-E3C764A28ACA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C56E8E4F-0182-4B47-AFC0-E3C764A28ACA", generation: 0)
,2017-07-12 07:46:10 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-12 07:46:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-12 07:46:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-12 07:46:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2ED3FB40-6060-4164-9F8E-D1A434C0CFD4/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-12 07:46:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-12 07:46:12 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
,2017-07-12 07:47:02 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-07-12 07:47:02 - DEBUG CoordinatedClient: 'test client failed'
2017-07-12 07:47:02 - DEBUG CoordinatedClient: '50000'
,2017-07-12 07:47:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-07-12 07:47:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
