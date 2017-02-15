#### Test 1062586553e7ecec_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/239B57EA-5117-489F-9D63-2D2133D60BEB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/239B57EA-5117-489F-9D63-2D2133D60BEB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55496"
,(lldb)     command script import "/tmp/239B57EA-5117-489F-9D63-2D2133D60BEB/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-15 13:07:49.156 ThaliTest[3748:10564468] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/21D7720B-7725-4DD0-9208-32CE636F96BB/Library/Cookies/Cookies.binarycookies
,2017-02-15 13:07:49.282 ThaliTest[3748:10564468] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-15 13:07:49.284 ThaliTest[3748:10564468] Multi-tasking -> Device: YES, App: YES
,2017-02-15 13:07:49.304 ThaliTest[3748:10564468] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-15 13:07:51.136 ThaliTest[3748:10564468] Using UIWebView
,2017-02-15 13:07:51.145 ThaliTest[3748:10564468] [CDVTimer][handleopenurl] 0.450015ms
,2017-02-15 13:07:51.154 ThaliTest[3748:10564468] [CDVTimer][intentandnavigationfilter] 8.109987ms
2017-02-15 13:07:51.155 ThaliTest[3748:10564468] [CDVTimer][gesturehandler] 0.420988ms
2017-02-15 13:07:51.155 ThaliTest[3748:10564468] [CDVTimer][TotalPluginStartup] 10.963976ms
,2017-02-15 13:07:58.840 ThaliTest[3748:10564468] Resetting plugins due to page load.
,2017-02-15 13:08:03.600 ThaliTest[3748:10564468] Finished load of: file:///var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/index.html
,2017-02-15 13:08:03.791 ThaliTest[3748:10564468] JXcore Cordova plugin initializing
,2017-02-15 13:08:03.791 ThaliTest[3748:10564687] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-15 12:08:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-15 12:08:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-15 12:08:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-15 12:08:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-02-15 12:08:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-15 12:08:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-15 12:08:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-15 12:08:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.61227798461914
,2017-02-15 12:08:44 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-02-15 12:08:44 - WARN testUtils: 'myNameCallback not set!'
,2017-02-15 12:08:47 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-15 12:08:47 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-15 12:08:47 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-15 12:08:49 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-15 12:08:49 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-15 12:08:49 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-15 12:08:49 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-15 12:08:49 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-15 12:08:49 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-15 12:08:52 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-15 12:08:52 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-15 12:08:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2017-02-15 13:08:52.298 ThaliTest[3748:10564468] THREAD WARNING: ['JXcore'] took '13.861816' ms. Plugin should use a background thread.
,2017-02-15 12:08:52 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-15 12:08:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:08:55 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-02-15 12:08:55 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-15 12:13:57 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-15 12:13:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:13:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:16:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:17:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:18:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:19:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:20:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:21:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:22:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:23:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:24:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:25:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:26:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:27:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2,DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:28:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/618FC817,-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/618FC817-2DD9-404A-B440-67E23EE158F3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
