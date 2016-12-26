#### Test 969189473645b2d_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/EB74529B-C86B-4046-B957-A1875152D65C/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/EB74529B-C86B-4046-B957-A1875152D65C/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49480"
,(lldb)     command script import "/tmp/EB74529B-C86B-4046-B957-A1875152D65C/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 16:55:58.186 ThaliTest[961:2904842] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/013D7C9C-C94F-401C-96FD-768A1A8237B9/Library/Cookies/Cookies.binarycookies
,2016-12-26 16:55:58.327 ThaliTest[961:2904842] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 16:55:58.330 ThaliTest[961:2904842] Multi-tasking -> Device: YES, App: YES
,2016-12-26 16:55:58.355 ThaliTest[961:2904842] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 16:55:59.000 ThaliTest[961:2904842] Using UIWebView
,2016-12-26 16:55:59.006 ThaliTest[961:2904842] [CDVTimer][handleopenurl] 0.593007ms
,2016-12-26 16:55:59.014 ThaliTest[961:2904842] [CDVTimer][intentandnavigationfilter] 7.318020ms
2016-12-26 16:55:59.015 ThaliTest[961:2904842] [CDVTimer][gesturehandler] 0.366986ms
2016-12-26 16:55:59.015 ThaliTest[961:2904842] [CDVTimer][TotalPluginStartup] 9.667039ms
,2016-12-26 16:56:07.796 ThaliTest[961:2904842] Resetting plugins due to page load.
,2016-12-26 16:56:08.470 ThaliTest[961:2904842] Finished load of: file:///var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/index.html
,2016-12-26 16:56:08.708 ThaliTest[961:2904842] JXcore Cordova plugin initializing
,2016-12-26 16:56:08.710 ThaliTest[961:2904998] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 15:56:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 15:56:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 15:56:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-26 15:56:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-26 15:56:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 15:56:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-26 15:56:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 15:57:17 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.22394895553589
,2016-12-26 15:57:17 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-12-26 15:57:17 - DEBUG UnitTest_app: 'My device name is: Apple-ipad-mini-mfts'
2016-12-26 15:57:17 - WARN testUtils: 'myNameCallback not set!'
,2016-12-26 15:57:25 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2016-12-26 15:57:25 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-26 15:57:26 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-26 15:57:26 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-26 15:57:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-26 15:57:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-26 15:57:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-26 15:57:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-26 15:57:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-26 15:57:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-26 15:57:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-26 15:57:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-26 15:57:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-26 15:57:35 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-26 15:57:35 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-26 15:57:36 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-26 15:57:36 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-26 15:57:36 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-26 15:57:36 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-26 15:57:36 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-26 15:57:36 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-26 15:57:36 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-26 15:57:37 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-26 15:57:38 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-26 16:57:38.152 ThaliTest[961:2904842] THREAD WARNING: ['JXcore'] took '20705.488037' ms. Plugin should use a background thread.
,2016-12-26 16:57:38.154 ThaliTest[961:2904983] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode,
,2016-12-26 15:57:38 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/node_modules/engine.io-client,/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Applica,tion/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 15:57:38 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 15:57:38 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/node_modules/engi,ne.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
on,Error@/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD82D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/279357F3-ACA9-49D9-A2F2-524105BFD,82D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 15:57:38 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
