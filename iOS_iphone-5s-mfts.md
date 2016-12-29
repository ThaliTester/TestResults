#### Test 99446918ca12220_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99446918ca12220/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DA12FF8C-3D16-428C-9EE6-5DDB0F742499/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/DA12FF8C-3D16-428C-9EE6-5DDB0F742499/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99446918ca12220/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99446918ca12220/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/04229ECE-1385-46E6-A126-3BB18FC86E07/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57856"
,(lldb)     command script import "/tmp/DA12FF8C-3D16-428C-9EE6-5DDB0F742499/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 12:05:57.682 ThaliTest[1416:2706428] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/26DC391D-0B57-4DC8-AB78-B198FBE75A65/Library/Cookies/Cookies.binarycookies
,2016-12-29 12:05:57.793 ThaliTest[1416:2706428] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 12:05:57.796 ThaliTest[1416:2706428] Multi-tasking -> Device: YES, App: YES
,2016-12-29 12:05:57.819 ThaliTest[1416:2706428] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 12:05:58.277 ThaliTest[1416:2706428] Using UIWebView
,2016-12-29 12:05:58.286 ThaliTest[1416:2706428] [CDVTimer][handleopenurl] 0.560999ms
,2016-12-29 12:05:58.297 ThaliTest[1416:2706428] [CDVTimer][intentandnavigationfilter] 10.605037ms
2016-12-29 12:05:58.298 ThaliTest[1416:2706428] [CDVTimer][gesturehandler] 0.364006ms
2016-12-29 12:05:58.298 ThaliTest[1416:2706428] [CDVTimer][TotalPlugin,Startup] 13.457000ms
,2016-12-29 12:06:04.022 ThaliTest[1416:2706428] Resetting plugins due to page load.
,2016-12-29 12:06:04.492 ThaliTest[1416:2706428] Finished load of: file:///var/containers/Bundle/Application/04229ECE-1385-46E6-A126-3BB18FC86E07/ThaliTest.app/www/index.html
,2016-12-29 12:06:04.884 ThaliTest[1416:2706428] JXcore Cordova plugin initializing
,2016-12-29 12:06:04.885 ThaliTest[1416:2706604] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 11:06:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 11:06:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 11:06:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-29 11:06:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 11:06:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-29 11:06:43 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.33611100912094
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
