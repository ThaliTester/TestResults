#### Test 103691986c90445e_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C9570A5E-653D-4553-9C1D-036CFF3E5E66/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/C9570A5E-653D-4553-9C1D-036CFF3E5E66/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FDE8E43D-D731-4054-AF5D-171148F62F11/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54176"
,(lldb)     command script import "/tmp/C9570A5E-653D-4553-9C1D-036CFF3E5E66/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-30 09:36:05.665 ThaliTest[937:2337007] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5B2EE4B6-63CA-4FE5-953E-A5CEC6D49C21/Library/Cookies/Cookies.binarycookies
,2017-01-30 09:36:05.755 ThaliTest[937:2337007] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-30 09:36:05.757 ThaliTest[937:2337007] Multi-tasking -> Device: YES, App: YES
,2017-01-30 09:36:05.775 ThaliTest[937:2337007] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-30 09:36:06.272 ThaliTest[937:2337007] Using UIWebView
,2017-01-30 09:36:06.280 ThaliTest[937:2337007] [CDVTimer][handleopenurl] 0.433028ms
,2017-01-30 09:36:06.291 ThaliTest[937:2337007] [CDVTimer][intentandnavigationfilter] 9.863019ms
2017-01-30 09:36:06.292 ThaliTest[937:2337007] [CDVTimer][gesturehandler] 0.388980ms
2017-01-30 09:36:06.292 ThaliTest[937:2337007] [CDVTimer][TotalPluginStar,tup] 12.715995ms
,2017-01-30 09:36:12.160 ThaliTest[937:2337007] Resetting plugins due to page load.
,2017-01-30 09:36:12.586 ThaliTest[937:2337007] Finished load of: file:///var/containers/Bundle/Application/FDE8E43D-D731-4054-AF5D-171148F62F11/ThaliTest.app/www/index.html
,2017-01-30 09:36:12.975 ThaliTest[937:2337007] JXcore Cordova plugin initializing
,2017-01-30 09:36:12.976 ThaliTest[937:2337184] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-30 08:36:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-30 08:36:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-30 08:36:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-30 08:36:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-30 08:36:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-30 08:36:53 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.06988400220871
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
