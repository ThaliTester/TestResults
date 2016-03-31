#### Test 646138038d447f5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/6641B1A7-C263-4BE7-906C-F70E4067B053/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6641B1A7-C263-4BE7-906C-F70E4067B053/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49575"
,(lldb)     command script import "/tmp/6641B1A7-C263-4BE7-906C-F70E4067B053/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 09:41:18.137 ThaliTest[2552:4695879] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35CB046C-904C-47D5-AB3A-21617024C19A/Library/Cookies/Cookies.binarycookies
,2016-03-31 09:41:18.387 ThaliTest[2552:4695879] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 09:41:18.388 ThaliTest[2552:4695879] Multi-tasking -> Device: YES, App: YES
,2016-03-31 09:41:18.408 ThaliTest[2552:4695879] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 09:41:19.211 ThaliTest[2552:4695879] Using UIWebView
,2016-03-31 09:41:19.216 ThaliTest[2552:4695879] [CDVTimer][handleopenurl] 0.149012ms
2016-03-31 09:41:19.219 ThaliTest[2552:4695879] [CDVTimer][intentandnavigationfilter] 2.729058ms
2016-03-31 09:41:19.219 ThaliTest[2552:4695879] [CDVTimer][gesturehandle,r] 0.136971ms
2016-03-31 09:41:19.219 ThaliTest[2552:4695879] [CDVTimer][TotalPluginStartup] 3.681004ms
,2016-03-31 09:41:22.414 ThaliTest[2552:4695879] Resetting plugins due to page load.
,2016-03-31 09:41:23.838 ThaliTest[2552:4695879] Finished load of: file:///var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/index.html
,2016-03-31 09:41:24.027 ThaliTest[2552:4695879] JXcore Cordova plugin initializing
,2016-03-31 09:41:24.029 ThaliTest[2552:4696045] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 09:41:32.304 ThaliTest[2552:4696045] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 09:41:32.305 ThaliTest[2552:4696045] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 09:41:32.306 ThaliTest[2552:4696045] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 09:41:32.308 ThaliTest[2552:4696045] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9D3FDF0F-7EEE-46EA-A028-93E8A0E2AC38/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,Connected to the test server

```
