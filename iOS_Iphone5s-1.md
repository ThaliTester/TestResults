#### Test 68102130aff19f4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130aff19f4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F9AAB33D-DCCB-4B32-9239-8EEACAA38195/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F9AAB33D-DCCB-4B32-9239-8EEACAA38195/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130aff19f4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130aff19f4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55022"
,(lldb)     command script import "/tmp/F9AAB33D-DCCB-4B32-9239-8EEACAA38195/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-28 17:14:16.692 ThaliTest[3802:8883812] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B0BB40C3-CAA9-4747-9C2B-19633AA34DDA/Library/Cookies/Cookies.binarycookies
,2016-04-28 17:14:17.100 ThaliTest[3802:8883812] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-28 17:14:17.102 ThaliTest[3802:8883812] Multi-tasking -> Device: YES, App: YES
,2016-04-28 17:14:17.126 ThaliTest[3802:8883812] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 17:14:19.261 ThaliTest[3802:8883812] Using UIWebView
,2016-04-28 17:14:19.268 ThaliTest[3802:8883812] [CDVTimer][handleopenurl] 0.554025ms
,2016-04-28 17:14:19.277 ThaliTest[3802:8883812] [CDVTimer][intentandnavigationfilter] 8.183956ms
2016-04-28 17:14:19.278 ThaliTest[3802:8883812] [CDVTimer][gesturehandler] 0.415981ms
2016-04-28 17:14:19.278 ThaliTest[3802:8883812] [CDVTimer][TotalPluginStartup] 11.004984ms
,2016-04-28 17:14:26.858 ThaliTest[3802:8883812] Resetting plugins due to page load.
,2016-04-28 17:14:30.719 ThaliTest[3802:8883812] Finished load of: file:///var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/index.html
,2016-04-28 17:14:30.965 ThaliTest[3802:8883812] JXcore Cordova plugin initializing
,2016-04-28 17:14:30.966 ThaliTest[3802:8884028] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 17:14:39.786 ThaliTest[3802:8884028] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-28 17:14:39.787 ThaliTest[3802:8884028] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-28 17:14:39.787 ThaliTest[3802:8884028] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 17:14:39.789 ThaliTest[3802:8884028] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/905BFFF1-5E95-469A-8BC3-57DB91EAE603/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 17:14:46.915 ThaliTest[3802:8883812] THREAD WARNING: ['JXcore'] took '6756.354248' ms. Plugin should use a background thread.

```
