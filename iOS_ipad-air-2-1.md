#### Test 1062586553e7ecec_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F5FED478-08DD-490C-A605-FA1192BA43B2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F5FED478-08DD-490C-A605-FA1192BA43B2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55494"
,(lldb)     command script import "/tmp/F5FED478-08DD-490C-A605-FA1192BA43B2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-15 13:07:39.046 ThaliTest[3680:10691299] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/31661A40-8FE3-46C6-8FED-8B118FF3CF0F/Library/Cookies/Cookies.binarycookies
,2017-02-15 13:07:39.400 ThaliTest[3680:10691299] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-15 13:07:39.402 ThaliTest[3680:10691299] Multi-tasking -> Device: YES, App: YES
,2017-02-15 13:07:39.420 ThaliTest[3680:10691299] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-15 13:07:41.606 ThaliTest[3680:10691299] Using UIWebView
,2017-02-15 13:07:41.615 ThaliTest[3680:10691299] [CDVTimer][handleopenurl] 0.343025ms
,2017-02-15 13:07:41.622 ThaliTest[3680:10691299] [CDVTimer][intentandnavigationfilter] 6.658018ms
,2017-02-15 13:07:41.623 ThaliTest[3680:10691299] [CDVTimer][gesturehandler] 0.277042ms
,2017-02-15 13:07:41.623 ThaliTest[3680:10691299] [CDVTimer][TotalPluginStartup] 8.826971ms
,2017-02-15 13:07:48.572 ThaliTest[3680:10691299] Resetting plugins due to page load.
,2017-02-15 13:07:52.028 ThaliTest[3680:10691299] Finished load of: file:///var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/index.html
,2017-02-15 13:07:52.304 ThaliTest[3680:10691299] JXcore Cordova plugin initializing
,2017-02-15 13:07:52.305 ThaliTest[3680:10691557] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-15 12:08:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-15 12:08:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-15 12:08:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-15 12:08:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-02-15 12:08:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-15 12:08:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-15 12:08:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-15 12:08:32 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  28.79320901632309
,2017-02-15 12:08:32 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
2017-02-15 12:08:32 - WARN testUtils: 'myNameCallback not set!'
,2017-02-15 12:08:35 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-15 12:08:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-15 12:08:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-15 12:08:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-15 12:08:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-15 12:08:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-15 12:08:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-15 12:08:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-15 12:08:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-02-15 13:08:38.678 ThaliTest[3680:10691299] THREAD WARNING: ['JXcore'] took '10.437988' ms. Plugin should use a background thread.
,2017-02-15 12:08:38 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-15 12:08:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:08:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:08:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:08:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:08:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:08:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:08:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:09:01 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-02-15 12:09:01 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-15 12:13:56 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-15 12:13:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:13:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-02-15 12:23:45 - WARN CoordinatedClient: 'reconnect_error error ignor,ed for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.,io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5,EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053,-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/A7ADB053-5EFE-4492-B76C-BF766207ADF2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
