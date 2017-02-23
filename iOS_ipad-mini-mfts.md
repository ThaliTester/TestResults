#### Test 107380351ee7f847_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/107380351ee7f847/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/92A83A64-0ED2-440E-8603-6F1DA4B1B451/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/92A83A64-0ED2-440E-8603-6F1DA4B1B451/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/107380351ee7f847/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/107380351ee7f847/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62844"
,(lldb)     command script import "/tmp/92A83A64-0ED2-440E-8603-6F1DA4B1B451/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2017-02-23 11:43:55.887 ThaliTest[2740:11422917] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6BDBB88-E308-44E6-80F0-7445C5FA1C28/Library/Cookies/Cookies.binarycookies
,2017-02-23 11:43:56.060 ThaliTest[2740:11422917] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-23 11:43:56.063 ThaliTest[2740:11422917] Multi-tasking -> Device: YES, App: YES
,2017-02-23 11:43:56.092 ThaliTest[2740:11422917] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-23 11:43:56.603 ThaliTest[2740:11422917] Using UIWebView
,2017-02-23 11:43:56.611 ThaliTest[2740:11422917] [CDVTimer][handleopenurl] 0.392973ms
,2017-02-23 11:43:56.619 ThaliTest[2740:11422917] [CDVTimer][intentandnavigationfilter] 7.582009ms
2017-02-23 11:43:56.619 ThaliTest[2740:11422917] [CDVTimer][gesturehandler] 0.395000ms
2017-02-23 11:43:56.620 ThaliTest[2740:11422917] [CDVTimer][TotalPluginStartup] 9.760976ms
,2017-02-23 11:44:03.507 ThaliTest[2740:11422917] Resetting plugins due to page load.
,2017-02-23 11:44:03.998 ThaliTest[2740:11422917] Finished load of: file:///var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/index.html
,2017-02-23 11:44:04.350 ThaliTest[2740:11422917] JXcore Cordova plugin initializing
2017-02-23 11:44:04.354 ThaliTest[2740:11423070] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-02-23 10:44:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-02-23 10:44:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-02-23 10:44:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-23 10:44:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-02-23 10:44:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-23 10:44:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-02-23 10:44:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x1cca73d0> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 55
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser's mock node client received a message". in file: Optional("<unknown>"), line: 0
,2017-02-23 10:45:27 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  114
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  41.83583599328995
,Failed to execute UT.
,2017-02-23 10:45:27 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2017-02-23 10:45:27 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-mini-mfts''
2017-02-23 10:45:27 - WARN testUtils: 'myNameCallback not set!'
,2017-02-23 10:45:35 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-23 10:45:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-23 10:45:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-23 10:45:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-23 10:45:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-23 10:45:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-23 10:45:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-23 10:45:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-23 10:45:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-23 10:45:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-23 10:45:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-23 10:45:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-23 10:45:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-23 10:45:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-23 10:45:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-23 10:45:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-23 10:45:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-23 10:45:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-23 10:45:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-23 10:45:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-23 10:45:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-23 10:45:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-23 10:45:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-23 10:45:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-23 10:45:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-23 10:45:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-23 10:45:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-23 10:45:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-23 10:45:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-23 10:45:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-23 10:45:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-23 10:45:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn,'t registered
,2017-02-23 11:45:52.610 ThaliTest[2740:11422917] THREAD WARNING: ['JXcore'] took '19.890869' ms. Plugin should use a background thread.
,2017-02-23 10:45:52 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-23 10:45:53 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-23 10:45:53 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
,2017-02-23 10:45:53 - DEBUG CoordinatedClient: 'test client failed'
,2017-02-23 10:45:53 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-23 10:45:53 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF,/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:252:22
tryCatcher@/private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype.,_settlePromiseFromHandler@/private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/B,undle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CB,F9FF/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/BA29619E-C592-4DFE-B9B1-C656D3CBF9FF/ThaliTest.app/www/jxcore/node_modules/bluebird,/js/release/promise.js:691:13''
2017-02-23 10:45:53 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
