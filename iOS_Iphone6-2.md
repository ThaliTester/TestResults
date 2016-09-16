#### Test 8552588757d25d6_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C2EB60AF-A255-4116-A1BB-0F547EE3446D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/C2EB60AF-A255-4116-A1BB-0F547EE3446D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8AB69456-AA3A-4B1E-BF3D-7986D1AA0696/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51921"
,(lldb)     command script import "/tmp/C2EB60AF-A255-4116-A1BB-0F547EE3446D/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 00:06:48.835 ThaliTest[899:969700] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF9F67F8-31E1-441A-8B1F-E2B025AE0EE4/Library/Cookies/Cookies.binarycookies
,2016-09-16 00:06:49.112 ThaliTest[899:969700] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 00:06:49.113 ThaliTest[899:969700] Multi-tasking -> Device: YES, App: YES
,2016-09-16 00:06:49.132 ThaliTest[899:969700] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 00:06:49.643 ThaliTest[899:969700] Using UIWebView
,2016-09-16 00:06:49.652 ThaliTest[899:969700] [CDVTimer][handleopenurl] 0.495017ms
,2016-09-16 00:06:49.660 ThaliTest[899:969700] [CDVTimer][intentandnavigationfilter] 7.027984ms
2016-09-16 00:06:49.661 ThaliTest[899:969700] [CDVTimer][gesturehandler] 0.334024ms
2016-09-16 00:06:49.661 ThaliTest[899:969700] [CDVTimer][TotalPluginStartup,] 9.528995ms
,2016-09-16 00:06:55.595 ThaliTest[899:969700] Resetting plugins due to page load.
,2016-09-16 00:06:55.892 ThaliTest[899:969700] Finished load of: file:///var/containers/Bundle/Application/8AB69456-AA3A-4B1E-BF3D-7986D1AA0696/ThaliTest.app/www/index.html
,2016-09-16 00:06:56.223 ThaliTest[899:969700] JXcore Cordova plugin initializing
,2016-09-16 00:06:56.224 ThaliTest[899:969892] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 00:07:02.836 ThaliTest[899:969892] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 00:07:02.837 ThaliTest[899:969892] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 00:07:02.837 ThaliTest[899:969892] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 00:07:02.839 ThaliTest[899:969892] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 00:07:03.220 ThaliTest[899:969892] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004242002964019775
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
