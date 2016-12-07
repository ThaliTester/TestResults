#### Test 9691894766ea5e0_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/EDCD358F-3C75-4028-833F-115B27C397C0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/EDCD358F-3C75-4028-833F-115B27C397C0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65522"
,(lldb)     command script import "/tmp/EDCD358F-3C75-4028-833F-115B27C397C0/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 15:38:27.252 ThaliTest[326:131726] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B1AAF694-796B-4E86-B85A-26A95B27C749/Library/Cookies/Cookies.binarycookies
,2016-12-07 15:38:27.291 ThaliTest[326:131726] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 15:38:27.292 ThaliTest[326:131726] Multi-tasking -> Device: YES, App: YES
,2016-12-07 15:38:27.302 ThaliTest[326:131726] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 15:38:27.637 ThaliTest[326:131726] Using UIWebView
,2016-12-07 15:38:27.642 ThaliTest[326:131726] [CDVTimer][handleopenurl] 0.248015ms
,2016-12-07 15:38:27.648 ThaliTest[326:131726] [CDVTimer][intentandnavigationfilter] 5.899966ms
2016-12-07 15:38:27.649 ThaliTest[326:131726] [CDVTimer][gesturehandler] 0.196993ms
2016-12-07 15:38:27.649 ThaliTest[326:131726] [CDVTimer][TotalPluginStartup,] 7.498026ms
,2016-12-07 15:38:33.446 ThaliTest[326:131726] Resetting plugins due to page load.
,2016-12-07 15:38:33.975 ThaliTest[326:131726] Finished load of: file:///var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/index.html
,2016-12-07 15:38:34.383 ThaliTest[326:131726] JXcore Cordova plugin initializing
,2016-12-07 15:38:34.384 ThaliTest[326:131892] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 14:38:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 14:38:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 14:38:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-07 14:38:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 14:38:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 14:38:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-07 14:38:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,2016-12-07 14:39:25 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  39.87239795923233
F,ailed to execute UT.
2016-12-07 14:39:25 - DEBUG UnitTest_app: 'Failed to execute UT.'
2016-12-07 14:39:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForegro,und wasn't registered
appEnteringBackground wasn't registered
,2016-12-07 14:39:25 - DEBUG UnitTest_app: 'My device name is: Apple-iphone-6-2'
2016-12-07 14:39:25 - WARN testUtils: 'myNameCallback not set!'
,2016-12-07 14:39:27 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-12-07 14:39:27 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-07 14:39:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-07 14:39:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-07 14:39:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-07 14:39:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-07 14:39:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-07 14:39:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-07 14:39:31 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-07 14:39:32 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-12-07 14:39:33 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
,2016-12-07 14:39:33 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-07 14:39:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-12-07 14:39:33 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C,/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:250:22
tryCatcher@/private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype.,_settlePromiseFromHandler@/private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/B,undle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29C,A95C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/6FF8D49F-06DB-464A-9430-C7ABA29CA95C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
,2016-12-07 14:39:33 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
