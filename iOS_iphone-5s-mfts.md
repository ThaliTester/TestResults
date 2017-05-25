#### Test 11335185108be6d0_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185108be6d0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DEC21059-D035-46D1-A558-9986331331D0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/DEC21059-D035-46D1-A558-9986331331D0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185108be6d0/build_ios/ThaliTest.app"
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185108be6d0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54070"
,(lldb)     command script import "/tmp/DEC21059-D035-46D1-A558-9986331331D0/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-05-25 11:49:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-25 11:49:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-25 11:49:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-25 11:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-25 11:49:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-25 11:49:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-25 11:49:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-05-25 11:49:04 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
(lldb) ,Number of failed tests:  0
,Number of ignored tests:  0
(lldb) ,Total duration:  1.536437928676605
,2017-05-25 11:49:04 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
(lldb) ,2017-05-25 11:49:04 - WARN testUtils: 'myNameCallback not set!'
,2017-05-25 11:49:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-25 11:49:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-25 11:49:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-25 11:49:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-25 11:49:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-25 11:49:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DA4E21DB-28FF-497F-844F-85F168822249/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-25 11:49:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-05-25 11:49:11 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-05-25 11:50:01 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-25 11:50:01 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-05-25 11:50:01 - DEBUG CoordinatedClient: '50000'
2017-05-25 11:50:01 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-05-25 11:50:01 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
