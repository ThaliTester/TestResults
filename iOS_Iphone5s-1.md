#### Test 6012434764ab483_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/4ACA87C6-7569-49F0-8F7F-13975A9ED6A0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4ACA87C6-7569-49F0-8F7F-13975A9ED6A0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49657"
,(lldb)     command script import "/tmp/4ACA87C6-7569-49F0-8F7F-13975A9ED6A0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 02:36:50.775 ThaliTest[946:1423898] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E195A8D5-DCC0-42AB-A015-6812D693F216/Library/Cookies/Cookies.binarycookies
,2016-03-09 02:36:51.145 ThaliTest[946:1423898] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-09 02:36:51.146 ThaliTest[946:1423898] Multi-tasking -> Device: YES, App: YES
,2016-03-09 02:36:51.169 ThaliTest[946:1423898] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 02:36:52.761 ThaliTest[946:1423898] Using UIWebView
,2016-03-09 02:36:52.768 ThaliTest[946:1423898] [CDVTimer][handleopenurl] 0.550032ms
,2016-03-09 02:36:52.777 ThaliTest[946:1423898] [CDVTimer][intentandnavigationfilter] 8.078992ms
2016-03-09 02:36:52.778 ThaliTest[946:1423898] [CDVTimer][gesturehandler] 0.397027ms
2016-03-09 02:36:52.779 ThaliTest[946:1423898] [CDVTimer][TotalPluginStartup] 10.940015ms
,2016-03-09 02:37:00.213 ThaliTest[946:1423898] Resetting plugins due to page load.
,2016-03-09 02:37:04.152 ThaliTest[946:1423898] Finished load of: file:///var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/index.html
,2016-03-09 02:37:04.482 ThaliTest[946:1423898] JXcore Cordova plugin initializing
2016-03-09 02:37:04.483 ThaliTest[946:1424131] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-09 02:37:13.245 ThaliTest[946:1424131] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-09 02:37:13.246 ThaliTest[946:1424131] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-09 02:37:13.246 ThaliTest[946:1424131] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-09 02:37:13.250 ThaliTest[946:1424131] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E34F9FA6-6612-4E0F-B3C6-63F1DCF28941/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
