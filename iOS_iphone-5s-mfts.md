#### Test 99572749eaf5166_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99572749eaf5166/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/36FCECAF-0423-42E5-9314-A1843033096E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/36FCECAF-0423-42E5-9314-A1843033096E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99572749eaf5166/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99572749eaf5166/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9B7F2ACA-9CDC-4C3B-BC80-329B1D1A4237/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58505"
,(lldb)     command script import "/tmp/36FCECAF-0423-42E5-9314-A1843033096E/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 13:45:20.314 ThaliTest[1597:3320890] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/597C2BA6-394C-4E2D-B361-8BC6A454659A/Library/Cookies/Cookies.binarycookies
,2017-01-03 13:45:20.365 ThaliTest[1597:3320890] Apache Cordova native platform version 4.3.1 is starting.
2017-01-03 13:45:20.366 ThaliTest[1597:3320890] Multi-tasking -> Device: YES, App: YES
,2017-01-03 13:45:20.387 ThaliTest[1597:3320890] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 13:45:20.647 ThaliTest[1597:3320890] Using UIWebView
,2017-01-03 13:45:20.651 ThaliTest[1597:3320890] [CDVTimer][handleopenurl] 0.155985ms
,2017-01-03 13:45:20.656 ThaliTest[1597:3320890] [CDVTimer][intentandnavigationfilter] 4.290998ms
2017-01-03 13:45:20.656 ThaliTest[1597:3320890] [CDVTimer][gesturehandler] 0.162005ms
2017-01-03 13:45:20.656 ThaliTest[1597:3320890] [CDVTimer][TotalPluginStartup] 5.349040ms
,2017-01-03 13:45:24.059 ThaliTest[1597:3320890] Resetting plugins due to page load.
,2017-01-03 13:45:24.355 ThaliTest[1597:3320890] Finished load of: file:///var/containers/Bundle/Application/9B7F2ACA-9CDC-4C3B-BC80-329B1D1A4237/ThaliTest.app/www/index.html
,2017-01-03 13:45:24.755 ThaliTest[1597:3320890] JXcore Cordova plugin initializing
,2017-01-03 13:45:24.756 ThaliTest[1597:3321058] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 12:45:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-03 12:45:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 12:45:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-03 12:45:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-03 12:45:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-03 12:46:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.65275496244431
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
