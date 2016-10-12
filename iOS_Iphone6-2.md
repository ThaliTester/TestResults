#### Test 88838102571b7ae_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88838102571b7ae/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A2E552F5-8405-4564-B97A-93BA7C579C3C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/A2E552F5-8405-4564-B97A-93BA7C579C3C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88838102571b7ae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88838102571b7ae/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58329"
,(lldb)     command script import "/tmp/A2E552F5-8405-4564-B97A-93BA7C579C3C/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-10-12 06:29:12.502 ThaliTest[2275:3891780] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7DD483BD-D3A4-45FB-ABBE-2AECF0B5AF60/Library/Cookies/Cookies.binarycookies
,2016-10-12 06:29:12.540 ThaliTest[2275:3891780] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-12 06:29:12.541 ThaliTest[2275:3891780] Multi-tasking -> Device: YES, App: YES
,2016-10-12 06:29:12.554 ThaliTest[2275:3891780] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-12 06:29:12.939 ThaliTest[2275:3891780] Using UIWebView
,2016-10-12 06:29:12.945 ThaliTest[2275:3891780] [CDVTimer][handleopenurl] 0.220954ms
,2016-10-12 06:29:12.951 ThaliTest[2275:3891780] [CDVTimer][intentandnavigationfilter] 5.708992ms
2016-10-12 06:29:12.951 ThaliTest[2275:3891780] [CDVTimer][gesturehandler] 0.202000ms
2016-10-12 06:29:12.951 ThaliTest[2275:3891780] [CDVTimer][TotalPluginStartup] 7.233024ms
,2016-10-12 06:29:19.158 ThaliTest[2275:3891780] Resetting plugins due to page load.
,2016-10-12 06:29:19.608 ThaliTest[2275:3891780] Finished load of: file:///var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/index.html
,2016-10-12 06:29:20.026 ThaliTest[2275:3891780] JXcore Cordova plugin initializing
,2016-10-12 06:29:20.027 ThaliTest[2275:3891963] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-12 13:29:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-12 13:29:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-12 13:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-12 13:29:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-12 13:29:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-10-12 13:29:49 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  74
Number of passed tests:  74
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  19.42539000511169
201,6-10-12 13:29:49 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-12 13:29:50 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-2'
2016-10-12 13:29:50 - WARN testUtils: 'myNameCallback not set!'
2016-10-12 13:29:50 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-12 13:29:52 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-12 13:29:52 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-12 13:29:52 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-12 13:29:53 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-12 13:29:54 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-12 13:29:54 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-12 13:29:54 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-12 13:29:54 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-12 13:29:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-12 13:29:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-12 13:29:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:29:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 13:29:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 13:29:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 13:29:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 13:29:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:29:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:29:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:29:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:29:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:29:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 13:30:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 13:30:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BA4A08D,-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 06:30:10.467 ThaliTest[2275:3891963] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_,fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5,E,E6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/2BA4A08D-2B02-4,3DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumbe,r,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2,B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var,/,containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/2BA4A08D-2B02-4,3DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/j,x,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
,2016-10-12 13:30:10 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE61,64CBCBE/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at So,cket.prototype.emit@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/2BA4,A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_m,o,dules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Ma,nager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Appl,ication/2BA4A08D-2B02-43DF-9AA4-5EE6164CBCBE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/containers/Bundle/Application/2BA4A08D-2B02-43DF-9AA4-5EE6164CBC,BE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
,2016-10-12 13:30:10 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
