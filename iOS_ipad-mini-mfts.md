#### Test 1073803513406f60_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1073803513406f60/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/319B549A-E779-463C-9BEB-B84205B4432A/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/319B549A-E779-463C-9BEB-B84205B4432A/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1073803513406f60/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1073803513406f60/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64691"
,(lldb)     command script import "/tmp/319B549A-E779-463C-9BEB-B84205B4432A/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-23 12:37:45.140 ThaliTest[2753:11430886] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7845474C-FE30-4F09-87F6-A312B2E9FB8D/Library/Cookies/Cookies.binarycookies
,2017-02-23 12:37:45.317 ThaliTest[2753:11430886] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-23 12:37:45.320 ThaliTest[2753:11430886] Multi-tasking -> Device: YES, App: YES
,2017-02-23 12:37:45.352 ThaliTest[2753:11430886] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-23 12:37:45.880 ThaliTest[2753:11430886] Using UIWebView
,2017-02-23 12:37:45.888 ThaliTest[2753:11430886] [CDVTimer][handleopenurl] 0.395000ms
,2017-02-23 12:37:45.896 ThaliTest[2753:11430886] [CDVTimer][intentandnavigationfilter] 7.258952ms
2017-02-23 12:37:45.896 ThaliTest[2753:11430886] [CDVTimer][gesturehandler] 0.358999ms
2017-02-23 12:37:45.897 ThaliTest[2753:11430886] [CDVTimer][TotalPluginStartup] 9.422958ms
,2017-02-23 12:37:52.799 ThaliTest[2753:11430886] Resetting plugins due to page load.
,2017-02-23 12:37:53.395 ThaliTest[2753:11430886] Finished load of: file:///var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/index.html
,2017-02-23 12:37:53.656 ThaliTest[2753:11430886] JXcore Cordova plugin initializing
2017-02-23 12:37:53.659 ThaliTest[2753:11431028] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-23 11:38:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-23 11:38:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-23 11:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-23 11:38:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-02-23 11:38:32 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-02-23 11:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-02-23 11:38:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFai,led registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser peer found Advertiser peer". in file: Optional("<unknown>"), line: 0
,failed - BrowserManager does not have available peers to connect in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 133
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/VirtualSocketTests.swift"), line: 139
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/VirtualSocketTests.swift"), line: 93
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/VirtualSocketTests.swift"), line: 75
,2017-02-23 11:39:12 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  111
,Number of failed tests:  5
,Number of ignored tests:  0
,Total duration:  37.85509699583054
,Failed to execute UT.
,2017-02-23 11:39:12 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2017-02-23 11:39:12 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-mini-mfts''
,2017-02-23 11:39:12 - WARN testUtils: 'myNameCallback not set!'
,2017-02-23 11:39:24 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-23 11:39:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-23 11:39:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-23 11:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-23 11:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-23 11:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-23 11:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-23 11:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-23 11:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-23 11:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-23 11:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-23 11:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-23 11:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-23 11:39:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-23 11:39:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-23 11:39:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-23 11:39:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-23 11:39:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-23 11:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-23 11:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-23 11:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-23 11:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-23 11:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-23 11:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-23 11:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-23 11:39:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-23 11:39:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-23 11:39:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-23 11:39:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-23 11:39:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-23 11:39:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-23 11:39:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-23 11:39:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-23 11:39:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-23 11:39:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-23 11:39:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-23 11:39:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-23 11:39:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-23 11:39:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-23 11:39:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-23 11:39:56 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-02-23 11:39:56 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-23 11:39:56 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-23 11:39:57 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
2017-02-23 11:39:57 - DEBUG CoordinatedClient: 'test client failed'
2017-02-23 11:39:57 - DEBUG CoordinatedClient: 'device disco,nnected from the test server'
2017-02-23 11:39:57 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/AA660,D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:252:22
tryCatcher@/private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
mo,dule.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settleP,romise@/private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/,AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/AA660D8B-F9F1-475B-9CC7-CD96684DB2AC/ThaliTest.app/,www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
,2017-02-23 11:39:57 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
