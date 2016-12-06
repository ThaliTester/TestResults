#### Test 965242983906281_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/965242983906281/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/5D905D5F-A814-4120-A31D-6CB581B6DF93/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5D905D5F-A814-4120-A31D-6CB581B6DF93/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/965242983906281/build_ios/ThaliTest.app"
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Current executable set to '/Users/thali/Github/CI/builder/builds/965242983906281/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C9C376FB-D825-4854-8260-1C966808721A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52514"
,(lldb)     command script import "/tmp/5D905D5F-A814-4120-A31D-6CB581B6DF93/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-06 16:04:24.923 ThaliTest[308:134626] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/55A50826-0282-4F46-A41B-5B1A16959781/Library/Cookies/Cookies.binarycookies
(lldb) ,2016-12-06 16:04:25.286 ThaliTest[308:134626] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-06 16:04:25.287 ThaliTest[308:134626] Multi-tasking -> Device: YES, App: YES
(lldb) ,2016-12-06 16:04:25.305 ThaliTest[308:134626] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-06 16:04:27.594 ThaliTest[308:134626] Using UIWebView
(lldb) ,2016-12-06 16:04:27.602 ThaliTest[308:134626] [CDVTimer][handleopenurl] 0.328958ms
,2016-12-06 16:04:27.610 ThaliTest[308:134626] [CDVTimer][intentandnavigationfilter] 6.955981ms
(lldb) ,2016-12-06 16:04:27.610 ThaliTest[308:134626] [CDVTimer][gesturehandler] 0.318050ms
,2016-12-06 16:04:27.611 ThaliTest[308:134626] [CDVTimer][TotalPluginStartup] 9.208977ms
(lldb) ,2016-12-06 16:04:35.055 ThaliTest[308:134626] Resetting plugins due to page load.
(lldb) ,2016-12-06 16:04:38.893 ThaliTest[308:134626] Finished load of: file:///var/mobile/Containers/Bundle/Application/C9C376FB-D825-4854-8260-1C966808721A/ThaliTest.app/www/index.html
(lldb) ,2016-12-06 16:04:39.134 ThaliTest[308:134626] JXcore Cordova plugin initializing
,2016-12-06 16:04:39.135 ThaliTest[308:134902] JXcore instance initializing
(lldb) ,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
(lldb) ,Platform ios
Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2016-12-06 15:04:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2016-12-06 15:04:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-06 15:04:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-06 15:04:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2016-12-06 15:04:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
(lldb) ,Optional(false)
,Optional(true)
(lldb) ,failed - Unexpected connect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 39
(lldb) ,2016-12-06 15:05:14 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
(lldb) ,Total number of executed tests:  116
(lldb) ,Number of passed tests:  115
,Number of failed tests:  1
(lldb) ,Number of ignored tests:  0
,Total duration:  25.87687599658966
(lldb) ,Failed to execute UT.
,2016-12-06 15:05:14 - DEBUG UnitTest_app: 'Failed to execute UT.'
(lldb) ,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
