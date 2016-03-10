#### Test 6012434713fea37_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/04F7612C-1701-488E-B29F-9BA2ED60984C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/04F7612C-1701-488E-B29F-9BA2ED60984C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50060"
,(lldb)     command script import "/tmp/04F7612C-1701-488E-B29F-9BA2ED60984C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 02:43:11.765 ThaliTest[1010:1573757] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6933CE4D-8925-44A2-9BA5-929B634555DC/Library/Cookies/Cookies.binarycookies
,2016-03-10 02:43:12.141 ThaliTest[1010:1573757] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 02:43:12.142 ThaliTest[1010:1573757] Multi-tasking -> Device: YES, App: YES
,2016-03-10 02:43:12.168 ThaliTest[1010:1573757] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 02:43:14.019 ThaliTest[1010:1573757] Using UIWebView
,2016-03-10 02:43:14.029 ThaliTest[1010:1573757] [CDVTimer][handleopenurl] 0.485003ms
,2016-03-10 02:43:14.038 ThaliTest[1010:1573757] [CDVTimer][intentandnavigationfilter] 7.992029ms
2016-03-10 02:43:14.039 ThaliTest[1010:1573757] [CDVTimer][gesturehandler] 0.387013ms
2016-03-10 02:43:14.039 ThaliTest[1010:1573757] [CDVTimer][TotalPluginStartup] 10.916054ms
,2016-03-10 02:43:21.660 ThaliTest[1010:1573757] Resetting plugins due to page load.
,2016-03-10 02:43:25.304 ThaliTest[1010:1573757] Finished load of: file:///var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/index.html
,2016-03-10 02:43:25.564 ThaliTest[1010:1573757] JXcore Cordova plugin initializing
2016-03-10 02:43:25.565 ThaliTest[1010:1573999] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 02:43:34.328 ThaliTest[1010:1573999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 02:43:34.329 ThaliTest[1010:1573999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 02:43:34.329 ThaliTest[1010:1573999] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 02:43:34.333 ThaliTest[1010:1573999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/110F8C45-F91C-4ED5-86D7-FF131CA26224/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
