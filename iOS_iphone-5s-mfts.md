#### Test 10258170873f290a_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/27FCD833-F762-4365-B194-83DCBF60763E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/27FCD833-F762-4365-B194-83DCBF60763E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DC15FF8F-7E87-461F-A4DA-7C6C2D452EFC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59899"
,(lldb)     command script import "/tmp/27FCD833-F762-4365-B194-83DCBF60763E/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 12:36:16.832 ThaliTest[667:1504709] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/50C062E3-2ED1-4796-98CC-AE2A836A2E49/Library/Cookies/Cookies.binarycookies
,2017-01-24 12:36:16.926 ThaliTest[667:1504709] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 12:36:16.928 ThaliTest[667:1504709] Multi-tasking -> Device: YES, App: YES
,2017-01-24 12:36:16.947 ThaliTest[667:1504709] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 12:36:17.564 ThaliTest[667:1504709] Using UIWebView
,2017-01-24 12:36:17.573 ThaliTest[667:1504709] [CDVTimer][handleopenurl] 0.425994ms
,2017-01-24 12:36:17.583 ThaliTest[667:1504709] [CDVTimer][intentandnavigationfilter] 10.044038ms
2017-01-24 12:36:17.584 ThaliTest[667:1504709] [CDVTimer][gesturehandler] 0.362992ms
2017-01-24 12:36:17.585 ThaliTest[667:1504709] [CDVTimer][TotalPluginStartup] 12.928009ms
,2017-01-24 12:36:25.006 ThaliTest[667:1504709] Resetting plugins due to page load.
,2017-01-24 12:36:25.612 ThaliTest[667:1504709] Finished load of: file:///var/containers/Bundle/Application/DC15FF8F-7E87-461F-A4DA-7C6C2D452EFC/ThaliTest.app/www/index.html
,2017-01-24 12:36:26.044 ThaliTest[667:1504709] JXcore Cordova plugin initializing
,2017-01-24 12:36:26.045 ThaliTest[667:1504926] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 11:36:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-24 11:36:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 11:36:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-24 11:36:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-24 11:36:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-24 11:37:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.65355896949768
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
