#### Test 9691894766ea5e0_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/A0F71E5B-FC88-422A-A7FD-F3479E2E8532/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A0F71E5B-FC88-422A-A7FD-F3479E2E8532/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65529"
,(lldb)     command script import "/tmp/A0F71E5B-FC88-422A-A7FD-F3479E2E8532/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 15:38:37.457 ThaliTest[406:286355] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/36082BF7-3435-4736-8F5B-F38C45DBD9C3/Library/Cookies/Cookies.binarycookies
,2016-12-07 15:38:37.574 ThaliTest[406:286355] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 15:38:37.576 ThaliTest[406:286355] Multi-tasking -> Device: YES, App: YES
,2016-12-07 15:38:37.599 ThaliTest[406:286355] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 15:38:39.203 ThaliTest[406:286355] Using UIWebView
,2016-12-07 15:38:39.212 ThaliTest[406:286355] [CDVTimer][handleopenurl] 0.458002ms
,2016-12-07 15:38:39.223 ThaliTest[406:286355] [CDVTimer][intentandnavigationfilter] 10.223985ms
2016-12-07 15:38:39.224 ThaliTest[406:286355] [CDVTimer][gesturehandler] 0.392973ms
2016-12-07 15:38:39.224 ThaliTest[406:286355] [CDVTimer][TotalPluginStartu,p] 13.226986ms
,2016-12-07 15:38:45.252 ThaliTest[406:286355] Resetting plugins due to page load.
,2016-12-07 15:38:48.754 ThaliTest[406:286355] Finished load of: file:///var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/index.html
,2016-12-07 15:38:49.062 ThaliTest[406:286355] JXcore Cordova plugin initializing
,2016-12-07 15:38:49.063 ThaliTest[406:286581] JXcore instance initializing
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
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-07 14:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 14:39:26 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.21909296512604
,2016-12-07 14:39:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-12-07 14:39:27 - DEBUG UnitTest_app: 'My device name is: Apple-iphone-5s-1'
2016-12-07 14:39:27 - WARN testUtils: 'myNameCallback not set!'
,2016-12-07 14:39:29 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-12-07 14:39:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-07 14:39:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-07 14:39:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-07 14:39:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-07 14:39:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-07 14:39:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-07 14:39:34 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-07 14:39:34 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-12-07 14:43:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-12-07 14:43:02 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FB,C0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/en,gine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobi,le/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2016-12-07 14:43:02 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-07 14:43:02 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FB,C0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/en,gine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobi,le/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2016-12-07 14:43:02 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-07 14:43:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modul,es/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocke,t.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/7AA11194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/7AA11,194-0FAB-4F8A-9171-3628BC19FBC0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2016-12-07 14:43:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
