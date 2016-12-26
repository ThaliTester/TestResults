#### Test 969189473645b2d_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/27C8C127-78DB-459B-8205-4B0E62FC916C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/27C8C127-78DB-459B-8205-4B0E62FC916C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49828"
,(lldb)     command script import "/tmp/27C8C127-78DB-459B-8205-4B0E62FC916C/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 16:56:52.890 ThaliTest[1325:2422778] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/034FF321-5045-4705-84F5-7A43EC9135CD/Library/Cookies/Cookies.binarycookies
,2016-12-26 16:56:52.973 ThaliTest[1325:2422778] Apache Cordova native platform version 4.3.1 is starting.
2016-12-26 16:56:52.975 ThaliTest[1325:2422778] Multi-tasking -> Device: YES, App: YES
,2016-12-26 16:56:52.999 ThaliTest[1325:2422778] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 16:56:53.445 ThaliTest[1325:2422778] Using UIWebView
,2016-12-26 16:56:53.451 ThaliTest[1325:2422778] [CDVTimer][handleopenurl] 0.307024ms
,2016-12-26 16:56:53.460 ThaliTest[1325:2422778] [CDVTimer][intentandnavigationfilter] 8.157015ms
2016-12-26 16:56:53.461 ThaliTest[1325:2422778] [CDVTimer][gesturehandler] 0.322998ms
2016-12-26 16:56:53.461 ThaliTest[1325:2422778] [CDVTimer][TotalPluginS,tartup] 10.394990ms
,2016-12-26 16:56:59.380 ThaliTest[1325:2422778] Resetting plugins due to page load.
,2016-12-26 16:56:59.852 ThaliTest[1325:2422778] Finished load of: file:///var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/index.html
,2016-12-26 16:57:00.357 ThaliTest[1325:2422778] JXcore Cordova plugin initializing
,2016-12-26 16:57:00.357 ThaliTest[1325:2422961] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 15:57:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 15:57:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 15:57:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-26 15:57:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-26 15:57:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 15:57:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-26 15:57:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-26 15:57:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.21995902061462
2,016-12-26 15:57:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-12-26 15:57:37 - DEBUG UnitTest_app: 'My device name is: Apple-iphone-6-2'
2016-12-26 15:57:37 - WARN testUtils: 'myNameCallback not set!'
,2016-12-26 15:57:39 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2016-12-26 15:57:39 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-26 15:57:40 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-26 15:57:40 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-26 15:57:41 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-26 15:57:41 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-26 15:57:41 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-26 15:57:41 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-26 15:57:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-26 15:57:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-26 15:57:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-26 15:57:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-26 15:57:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-26 15:57:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-26 15:57:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-26 15:57:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-26 15:57:43 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-26 16:57:43.689 ThaliTest[1325:2422778] THREAD WARNING: ['JXcore'] took '6825.557129' ms. Plugin should use a background thread.
,2016-12-26 15:57:43 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 15:57:43 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 15:57:43 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/node_modules/engi,ne.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C3977B3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10775E09-5461-46CA-BFD8-04207C397,7B3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2016-12-26 15:57:43 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
