#### Test 9691894766ea5e0_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B26C1D4C-9D54-45FC-8D77-BF826DB337F0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/B26C1D4C-9D54-45FC-8D77-BF826DB337F0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49162"
,(lldb)     command script import "/tmp/B26C1D4C-9D54-45FC-8D77-BF826DB337F0/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 15:38:40.571 ThaliTest[337:150085] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A16F0A8E-31C3-4CF7-96E4-21DA0A51D5F6/Library/Cookies/Cookies.binarycookies
,2016-12-07 15:38:40.677 ThaliTest[337:150085] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 15:38:40.679 ThaliTest[337:150085] Multi-tasking -> Device: YES, App: YES
,2016-12-07 15:38:40.703 ThaliTest[337:150085] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 15:38:41.189 ThaliTest[337:150085] Using UIWebView
,2016-12-07 15:38:41.197 ThaliTest[337:150085] [CDVTimer][handleopenurl] 0.389993ms
,2016-12-07 15:38:41.207 ThaliTest[337:150085] [CDVTimer][intentandnavigationfilter] 10.012031ms
2016-12-07 15:38:41.208 ThaliTest[337:150085] [CDVTimer][gesturehandler] 0.355005ms
2016-12-07 15:38:41.208 ThaliTest[337:150085] [CDVTimer][TotalPluginStartup] 12.727022ms
,2016-12-07 15:38:47.588 ThaliTest[337:150085] Resetting plugins due to page load.
,2016-12-07 15:38:48.196 ThaliTest[337:150085] Finished load of: file:///var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/index.html
,2016-12-07 15:38:48.657 ThaliTest[337:150085] JXcore Cordova plugin initializing
,2016-12-07 15:38:48.658 ThaliTest[337:150291] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 14:39:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.39380699396133
,2016-12-07 14:39:27 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-12-07 14:39:27 - DEBUG UnitTest_app: 'My device name is: Apple-iphone-5s-mfts'
,2016-12-07 14:39:27 - WARN testUtils: 'myNameCallback not set!'
,2016-12-07 14:39:30 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-07 14:39:32 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-07 14:39:32 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-07 14:39:32 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-07 14:39:32 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-07 14:39:35 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-07 15:39:35.022 ThaliTest[337:150085] THREAD WARNING: ['JXcore'] took '7594.878174' ms. Plugin should use a background thread.
,2016-12-07 14:39:35 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-12-07 14:43:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-12-07 14:43:02 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/engine.io-client,/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Applica,tion/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-07 14:43:02 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-07 14:43:02 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/engine.io-client,/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Applica,tion/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-07 14:43:02 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-07 14:43:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/engi,ne.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
on,Error@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5833/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8DD3E897-0766-45A1-BAEE-F246BEFD5,833/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-07 14:43:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
