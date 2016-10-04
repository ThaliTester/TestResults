#### Test 878597992c267bc_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B3FF4AB7-5A2D-43D9-938D-4BFBAB66BD91/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/B3FF4AB7-5A2D-43D9-938D-4BFBAB66BD91/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55077"
,(lldb)     command script import "/tmp/B3FF4AB7-5A2D-43D9-938D-4BFBAB66BD91/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-04 02:46:35.548 ThaliTest[2017:2984681] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1938F7E-CEF6-4B96-9766-6A7CB58245EE/Library/Cookies/Cookies.binarycookies
,2016-10-04 02:46:35.627 ThaliTest[2017:2984681] Apache Cordova native platform version 4.2.1 is starting.
2016-10-04 02:46:35.628 ThaliTest[2017:2984681] Multi-tasking -> Device: YES, App: YES
,2016-10-04 02:46:35.645 ThaliTest[2017:2984681] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-04 02:46:36.067 ThaliTest[2017:2984681] Using UIWebView
,2016-10-04 02:46:36.077 ThaliTest[2017:2984681] [CDVTimer][handleopenurl] 0.326991ms
,2016-10-04 02:46:36.086 ThaliTest[2017:2984681] [CDVTimer][intentandnavigationfilter] 8.879006ms
2016-10-04 02:46:36.087 ThaliTest[2017:2984681] [CDVTimer][gesturehandler] 0.295043ms
2016-10-04 02:46:36.087 ThaliTest[2017:2984681] [CDVTimer][TotalPluginS,tartup] 11.191010ms
,2016-10-04 02:46:41.784 ThaliTest[2017:2984681] Resetting plugins due to page load.
,2016-10-04 02:46:42.117 ThaliTest[2017:2984681] Finished load of: file:///var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/index.html
,2016-10-04 02:46:42.455 ThaliTest[2017:2984681] JXcore Cordova plugin initializing
,2016-10-04 02:46:42.456 ThaliTest[2017:2984864] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-04 09:46:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-04 09:46:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-04 09:46:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-04 09:46:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-04 09:46:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x15f92cab0>
,Optional("EAE6F9CB-456F-4470-A863-E7F358A8578E")
nil
,nil
,Optional("BFB6D1FC-7DF6-4E29-B8E6-B21061F8231E")
,Optional("9DC2974D-9215-4FCC-AD70-87DA1A17B7CC")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-04 09:47:08 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  60
Number of passed tests:  60
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  15.53834700584412
201,6-10-04 09:47:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-04 09:47:09 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-2'
2016-10-04 09:47:09 - WARN testUtils: 'myNameCallback not set!'
2016-10-04 09:47:09 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-04 09:47:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-04 09:47:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-04 09:47:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-04 09:47:14 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-04 02:47:15.027 ThaliTest[2017:2984681] THREAD WARNING: ['JXcore'] took '6189.752197' ms. Plugin should use a background thread.
,2016-10-04 09:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F,-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
2016-10-04 02:47:28.822 ThaliTest[2017:2984864] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Appl,ication/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers,/,Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node,_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager,.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:5,07:5"},{"_fileName":"/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnN,umber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/contai,ners/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototy,pe.connect/errorSub<@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8,A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/,Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/Tha,liTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30,-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-04 09:47:28 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedCli,ent.prototype._error@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-1,0C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/sock,et.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/contai,ners/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB,5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/socket.io-c,lient/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.pr,ototype.onError@/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
,2016-10-04 09:47:28 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/containers/Bundle/Application/031A549F-2ECC-44CD-8A30-10C1DAB5EB7C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js 220:0)


```
