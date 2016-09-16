#### Test 8552588750d17b9_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F1FCC725-D8A7-4F24-B84E-946A1C3203CD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F1FCC725-D8A7-4F24-B84E-946A1C3203CD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EB359028-65F5-48DC-BC88-6E36CFBB093B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60198"
,(lldb)     command script import "/tmp/F1FCC725-D8A7-4F24-B84E-946A1C3203CD/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 01:59:17.329 ThaliTest[921:981045] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AA7841AC-1F28-466A-A1AA-A8DDD8D07952/Library/Cookies/Cookies.binarycookies
,2016-09-16 01:59:17.622 ThaliTest[921:981045] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 01:59:17.624 ThaliTest[921:981045] Multi-tasking -> Device: YES, App: YES
,2016-09-16 01:59:17.648 ThaliTest[921:981045] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 01:59:18.213 ThaliTest[921:981045] Using UIWebView
,2016-09-16 01:59:18.223 ThaliTest[921:981045] [CDVTimer][handleopenurl] 0.420988ms
,2016-09-16 01:59:18.233 ThaliTest[921:981045] [CDVTimer][intentandnavigationfilter] 9.229004ms
2016-09-16 01:59:18.234 ThaliTest[921:981045] [CDVTimer][gesturehandler] 0.389993ms
2016-09-16 01:59:18.234 ThaliTest[921:981045] [CDVTimer][TotalPluginStartup,] 11.739016ms
,2016-09-16 01:59:24.006 ThaliTest[921:981045] Resetting plugins due to page load.
,2016-09-16 01:59:24.480 ThaliTest[921:981045] Finished load of: file:///var/containers/Bundle/Application/EB359028-65F5-48DC-BC88-6E36CFBB093B/ThaliTest.app/www/index.html
,2016-09-16 01:59:24.879 ThaliTest[921:981045] JXcore Cordova plugin initializing
,2016-09-16 01:59:24.880 ThaliTest[921:981236] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 01:59:31.350 ThaliTest[921:981236] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 01:59:31.350 ThaliTest[921:981236] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 01:59:31.350 ThaliTest[921:981236] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 01:59:31.352 ThaliTest[921:981236] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 01:59:31.732 ThaliTest[921:981236] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004207015037536621
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
