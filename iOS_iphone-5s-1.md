#### Test 1027067425e01561_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/13513650-9CA3-4C7C-911E-94F33FCED8FE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/13513650-9CA3-4C7C-911E-94F33FCED8FE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50041"
,(lldb)     command script import "/tmp/13513650-9CA3-4C7C-911E-94F33FCED8FE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-13 15:48:58.715 ThaliTest[3662:10257983] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8847A521-8D0D-465F-8298-E409BA559CFE/Library/Cookies/Cookies.binarycookies
,2017-02-13 15:48:58.836 ThaliTest[3662:10257983] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-13 15:48:58.837 ThaliTest[3662:10257983] Multi-tasking -> Device: YES, App: YES
,2017-02-13 15:48:58.859 ThaliTest[3662:10257983] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-13 15:49:00.610 ThaliTest[3662:10257983] Using UIWebView
,2017-02-13 15:49:00.618 ThaliTest[3662:10257983] [CDVTimer][handleopenurl] 0.409007ms
,2017-02-13 15:49:00.627 ThaliTest[3662:10257983] [CDVTimer][intentandnavigationfilter] 8.307993ms
2017-02-13 15:49:00.628 ThaliTest[3662:10257983] [CDVTimer][gesturehandler] 0.390053ms
2017-02-13 15:49:00.629 ThaliTest[3662:10257983] [CDVTimer][TotalPluginStartup] 11.022985ms
,2017-02-13 15:49:07.545 ThaliTest[3662:10257983] Resetting plugins due to page load.
,2017-02-13 15:49:11.391 ThaliTest[3662:10257983] Finished load of: file:///var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/index.html
,2017-02-13 15:49:11.711 ThaliTest[3662:10257983] JXcore Cordova plugin initializing
,2017-02-13 15:49:11.712 ThaliTest[3662:10258205] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-02-13 14:49:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-13 14:49:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-13 14:49:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-13 14:49:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-02-13 14:49:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-13 14:49:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-13 14:49:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-02-13 14:49:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.90823400020599
,2017-02-13 14:49:51 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-02-13 14:49:51 - WARN testUtils: 'myNameCallback not set!'
,2017-02-13 14:49:54 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-13 14:49:54 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-13 14:49:54 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-13 14:49:54 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-13 14:49:54 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-13 14:49:55 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-13 14:49:56 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-13 14:49:58 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-13 14:49:58 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-02-13 15:49:58.689 ThaliTest[3662:10257983] THREAD WARNING: ['JXcore'] took '14.593262' ms. Plugin should use a background thread.
,2017-02-13 14:49:58 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-13 14:49:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:50:02 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-02-13 14:50:02 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-13 14:55:03 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-13 14:55:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:55:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:56:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:57:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:58:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 14:59:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:00:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-02-13 15:01:21 - WARN CoordinatedClient: 'reconnect_error error igno,r,ed for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.,io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5,
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4,E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:01:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:02:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:03:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:04:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:05:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:06:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:07:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:08:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-E,E30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 15:09:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6,-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/FA6DD9A6-EE30-4E99-A68B-6094FA59E2F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
