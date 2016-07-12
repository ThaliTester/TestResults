#### Test 72145431744cc2c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8ED989E8-0226-46A6-8252-589D37DDFC84/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8ED989E8-0226-46A6-8252-589D37DDFC84/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52632"
,(lldb)     command script import "/tmp/8ED989E8-0226-46A6-8252-589D37DDFC84/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-12 11:34:29.586 ThaliTest[217:10284] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ADC4B743-A3C5-46CD-B96D-66446D23942C/Library/Cookies/Cookies.binarycookies
,2016-07-12 11:34:30.133 ThaliTest[217:10284] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-12 11:34:30.136 ThaliTest[217:10284] Multi-tasking -> Device: YES, App: YES
,2016-07-12 11:34:30.172 ThaliTest[217:10284] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-12 11:34:32.169 ThaliTest[217:10284] Using UIWebView
,2016-07-12 11:34:32.175 ThaliTest[217:10284] [CDVTimer][handleopenurl] 0.333965ms
,2016-07-12 11:34:32.181 ThaliTest[217:10284] [CDVTimer][intentandnavigationfilter] 5.656004ms
2016-07-12 11:34:32.182 ThaliTest[217:10284] [CDVTimer][gesturehandler] 0.258029ms
2016-07-12 11:34:32.182 ThaliTest[217:10284] [CDVTimer][TotalPluginStartup] 7,.445037ms
,2016-07-12 11:34:39.898 ThaliTest[217:10284] Resetting plugins due to page load.
,2016-07-12 11:34:43.229 ThaliTest[217:10284] Finished load of: file:///var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/index.html
,2016-07-12 11:34:43.520 ThaliTest[217:10284] JXcore Cordova plugin initializing
,2016-07-12 11:34:43.521 ThaliTest[217:10508] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-12 11:34:51.297 ThaliTest[217:10508] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-12 11:34:51.297 ThaliTest[217:10508] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-12 11:34:51.297 ThaliTest[217:10508] j,xcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-12 11:34:51.299 ThaliTest[217:10508] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9301E6F3-3C6A-45DB-815F-58D18B34B4F3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-12 11:34:57.941 ThaliTest[217:10284] THREAD WARNING: ['JXcore'] took '6333.298096' ms. Plugin should use a background thread.

```
