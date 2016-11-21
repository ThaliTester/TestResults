#### Test 931424420cf4179_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5A65ADC2-225B-41CA-9FD3-F1A741FC9BB4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5A65ADC2-225B-41CA-9FD3-F1A741FC9BB4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49840"
,(lldb)     command script import "/tmp/5A65ADC2-225B-41CA-9FD3-F1A741FC9BB4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 14:28:35.779 ThaliTest[3791:9729412] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E0454651-B03A-41E5-B2EE-4D0EF6736DDB/Library/Cookies/Cookies.binarycookies
,2016-11-21 14:28:35.865 ThaliTest[3791:9729412] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 14:28:35.867 ThaliTest[3791:9729412] Multi-tasking -> Device: YES, App: YES
,2016-11-21 14:28:35.891 ThaliTest[3791:9729412] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 14:28:36.264 ThaliTest[3791:9729412] Using UIWebView
,2016-11-21 14:28:36.271 ThaliTest[3791:9729412] [CDVTimer][handleopenurl] 0.383019ms
,2016-11-21 14:28:36.279 ThaliTest[3791:9729412] [CDVTimer][intentandnavigationfilter] 6.892025ms
2016-11-21 14:28:36.279 ThaliTest[3791:9729412] [CDVTimer][gesturehandler] 0.272989ms
2016-11-21 14:28:36.280 ThaliTest[3791:9729412] [CDVTimer][TotalPluginS,tartup] 9.083986ms
,2016-11-21 14:28:41.351 ThaliTest[3791:9729412] Resetting plugins due to page load.
,2016-11-21 14:28:41.638 ThaliTest[3791:9729412] Finished load of: file:///var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/index.html
,2016-11-21 14:28:41.974 ThaliTest[3791:9729412] JXcore Cordova plugin initializing
,2016-11-21 14:28:41.975 ThaliTest[3791:9729615] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 13:28:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 13:28:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 13:28:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 13:28:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 13:28:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 13:28:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 13:29:18 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.08562397956848
,2016-11-21 13:29:18 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-11-21 13:29:18 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
,2016-11-21 13:29:18 - WARN testUtils: 'myNameCallback not set!'
,2016-11-21 13:29:20 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-11-21 13:29:20 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-21 13:29:21 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-21 13:29:21 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-21 13:29:22 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-21 13:29:22 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-21 13:29:22 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-21 13:29:22 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-21 13:29:23 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-21 13:29:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 13:29:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CD388438,-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 14:29:39.155 ThaliTest[3791:9729615] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_,fileName":"/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-2,7,5AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/CD388438-89BD-4,8FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumbe,r,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/CD388438-8,9BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var,/,containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/CD388438-89BD-4,8FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/j,x,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-11-21 13:29:39 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/,containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:223:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxco,re/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.protot,ype.emitAll@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/CD388438-,8,9BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/nod,e_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at, Emitter.prototype.emit@/private/var/containers/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/conta,iners/Bundle/Application/CD388438-89BD-48FB-844C-275AD4620971/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-11-21 13:29:39 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined
```
