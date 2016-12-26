#### Test 969189473645b2d_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D4ADE810-3366-4ED8-999E-CCDD68AB2A0D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/D4ADE810-3366-4ED8-999E-CCDD68AB2A0D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49836"
,(lldb)     command script import "/tmp/D4ADE810-3366-4ED8-999E-CCDD68AB2A0D/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 16:57:14.594 ThaliTest[1187:2352798] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7C0A00C6-A88D-4172-AD60-304ED41BEBFD/Library/Cookies/Cookies.binarycookies
,2016-12-26 16:57:14.644 ThaliTest[1187:2352798] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 16:57:14.645 ThaliTest[1187:2352798] Multi-tasking -> Device: YES, App: YES
,2016-12-26 16:57:14.658 ThaliTest[1187:2352798] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 16:57:14.984 ThaliTest[1187:2352798] Using UIWebView
,2016-12-26 16:57:14.988 ThaliTest[1187:2352798] [CDVTimer][handleopenurl] 0.283957ms
,2016-12-26 16:57:14.994 ThaliTest[1187:2352798] [CDVTimer][intentandnavigationfilter] 5.849004ms
2016-12-26 16:57:14.995 ThaliTest[1187:2352798] [CDVTimer][gesturehandler] 0.193000ms
2016-12-26 16:57:14.995 ThaliTest[1187:2352798] [CDVTimer][TotalPluginStartup] 7.342994ms
,2016-12-26 16:57:20.924 ThaliTest[1187:2352798] Resetting plugins due to page load.
,2016-12-26 16:57:21.377 ThaliTest[1187:2352798] Finished load of: file:///var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/index.html
,2016-12-26 16:57:21.766 ThaliTest[1187:2352798] JXcore Cordova plugin initializing
,2016-12-26 16:57:21.767 ThaliTest[1187:2352969] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 15:57:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 15:57:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 15:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-26 15:57:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-26 15:57:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 15:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-26 15:57:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-26 15:58:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.34555697441101
,2016-12-26 15:58:00 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-12-26 15:58:00 - DEBUG UnitTest_app: 'My device name is: Apple-iphone-5s-mfts'
,2016-12-26 15:58:00 - WARN testUtils: 'myNameCallback not set!'
,2016-12-26 15:58:03 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2016-12-26 15:58:03 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-26 15:58:03 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-26 15:58:03 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-26 15:58:05 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-26 15:58:05 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-26 15:58:05 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-26 15:58:05 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-26 15:58:06 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-26 15:58:06 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-26 15:58:06 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-26 15:58:06 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-26 15:58:06 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-26 15:58:06 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-26 15:58:06 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-26 15:58:07 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-26 15:58:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-26 16:58:07.843 ThaliTest[1187:2352798] THREAD WARNING: ['JXcore'] took '7416.591797' ms. Plugin should use a background thread.
,2016-12-26 15:58:07 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-12-26 16:02:45 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-12-26 16:02:45 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/engine.io-client,/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Applica,tion/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 16:02:45 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 16:02:45 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/engine.io-client,/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Applica,tion/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 16:02:45 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 16:02:45 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/engi,ne.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
on,Error@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2CDDD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/FE8B19E8-7EBA-4625-BFAD-0B7263B2C,DDD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2016-12-26 16:02:45 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
