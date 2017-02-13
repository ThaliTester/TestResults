#### Test 1027067425e01561_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6EEE6227-C37D-4DE5-A90D-263C815248C9/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/6EEE6227-C37D-4DE5-A90D-263C815248C9/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50035"
,(lldb)     command script import "/tmp/6EEE6227-C37D-4DE5-A90D-263C815248C9/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-13 15:48:05.889 ThaliTest[2462:9899155] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A364724A-3F78-4AFD-946C-16464286CF55/Library/Cookies/Cookies.binarycookies
,2017-02-13 15:48:06.042 ThaliTest[2462:9899155] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-13 15:48:06.046 ThaliTest[2462:9899155] Multi-tasking -> Device: YES, App: YES
,2017-02-13 15:48:06.078 ThaliTest[2462:9899155] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-13 15:48:06.845 ThaliTest[2462:9899155] Using UIWebView
,2017-02-13 15:48:06.851 ThaliTest[2462:9899155] [CDVTimer][handleopenurl] 0.499010ms
,2017-02-13 15:48:06.859 ThaliTest[2462:9899155] [CDVTimer][intentandnavigationfilter] 7.597983ms
2017-02-13 15:48:06.860 ThaliTest[2462:9899155] [CDVTimer][gesturehandler] 0.334978ms
2017-02-13 15:48:06.860 ThaliTest[2462:9899155] [CDVTimer][TotalPluginStartup] 9.838998ms
,2017-02-13 15:48:16.585 ThaliTest[2462:9899155] Resetting plugins due to page load.
,2017-02-13 15:48:17.300 ThaliTest[2462:9899155] Finished load of: file:///var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/index.html
,2017-02-13 15:48:17.552 ThaliTest[2462:9899155] JXcore Cordova plugin initializing
,2017-02-13 15:48:17.554 ThaliTest[2462:9899553] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-13 14:48:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-13 14:48:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-13 14:48:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-13 14:48:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-02-13 14:48:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-13 14:48:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-13 14:48:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-02-13 14:49:42 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
,Total duration:  43.97610598802567
,Failed to execute UT.
,2017-02-13 14:49:42 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2017-02-13 14:49:42 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-mini-mfts''
,2017-02-13 14:49:42 - WARN testUtils: 'myNameCallback not set!'
,2017-02-13 14:49:50 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-13 14:49:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-13 14:49:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-13 14:49:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-13 14:49:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-13 14:49:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-13 14:49:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-13 14:49:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-13 14:49:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-13 14:49:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-13 14:49:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-13 14:49:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-13 14:50:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-13 14:50:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-13 14:50:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-13 14:50:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-13 14:50:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-13 14:50:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-02-13 15:50:03.459 ThaliTest[2462:9899155] THREAD WARNING: ['JXcore'] took '38.361084' ms. Plugin should use a background thread.
,2017-02-13 14:50:03 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-13 14:50:03 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-13 14:50:04 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
,2017-02-13 14:50:04 - DEBUG CoordinatedClient: 'test client failed'
,2017-02-13 14:50:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-13 14:50:04 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04,/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:252:22
tryCatcher@/private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype.,_settlePromiseFromHandler@/private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/B,undle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A027210,78D04/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/DD421EC8-3B7E-4CF2-B8AC-A02721078D04/ThaliTest.app/www/jxcore/node_modules/bluebir,d/js/release/promise.js:691:13''
2017-02-13 14:50:04 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
