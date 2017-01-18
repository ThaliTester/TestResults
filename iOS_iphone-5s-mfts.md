#### Test 10191057309b3d0c_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10191057309b3d0c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A6EB0D22-B06C-4ACF-94CD-95813A11247B/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/A6EB0D22-B06C-4ACF-94CD-95813A11247B/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10191057309b3d0c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10191057309b3d0c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E9FB8CE9-E697-4750-A7D5-ECB4E47CD871/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61389"
,(lldb)     command script import "/tmp/A6EB0D22-B06C-4ACF-94CD-95813A11247B/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-18 12:37:42.097 ThaliTest[406:704506] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CA5A3CF8-FF00-4463-8CBC-33AD65AFFAD3/Library/Cookies/Cookies.binarycookies
,2017-01-18 12:37:42.198 ThaliTest[406:704506] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-18 12:37:42.201 ThaliTest[406:704506] Multi-tasking -> Device: YES, App: YES
,2017-01-18 12:37:42.222 ThaliTest[406:704506] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-18 12:37:42.686 ThaliTest[406:704506] Using UIWebView
,2017-01-18 12:37:42.695 ThaliTest[406:704506] [CDVTimer][handleopenurl] 0.438988ms
,2017-01-18 12:37:42.706 ThaliTest[406:704506] [CDVTimer][intentandnavigationfilter] 11.107981ms
2017-01-18 12:37:42.707 ThaliTest[406:704506] [CDVTimer][gesturehandler] 0.344992ms
2017-01-18 12:37:42.708 ThaliTest[406:704506] [CDVTimer][TotalPluginStartup] 13.786972ms
,2017-01-18 12:37:49.803 ThaliTest[406:704506] Resetting plugins due to page load.
,2017-01-18 12:37:50.176 ThaliTest[406:704506] Finished load of: file:///var/containers/Bundle/Application/E9FB8CE9-E697-4750-A7D5-ECB4E47CD871/ThaliTest.app/www/index.html
,2017-01-18 12:37:50.575 ThaliTest[406:704506] JXcore Cordova plugin initializing
,2017-01-18 12:37:50.576 ThaliTest[406:704712] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-18 11:38:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-18 11:38:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-18 11:38:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-18 11:38:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-18 11:38:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2017-01-18 11:38:30 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.47513401508331
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
