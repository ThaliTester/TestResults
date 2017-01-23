#### Test 102585911d0c1950_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/14F2EDCA-2880-4780-A4DD-E827121DAE72/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/14F2EDCA-2880-4780-A4DD-E827121DAE72/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8FAD72A4-94EC-4584-886D-8D845C0789E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52109"
,(lldb)     command script import "/tmp/14F2EDCA-2880-4780-A4DD-E827121DAE72/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-23 15:34:12.532 ThaliTest[628:1387966] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E17E4AD9-F901-4C37-9C0F-F6F4870798E8/Library/Cookies/Cookies.binarycookies
,2017-01-23 15:34:12.628 ThaliTest[628:1387966] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-23 15:34:12.630 ThaliTest[628:1387966] Multi-tasking -> Device: YES, App: YES
,2017-01-23 15:34:12.647 ThaliTest[628:1387966] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-23 15:34:13.276 ThaliTest[628:1387966] Using UIWebView
,2017-01-23 15:34:13.284 ThaliTest[628:1387966] [CDVTimer][handleopenurl] 0.398993ms
,2017-01-23 15:34:13.296 ThaliTest[628:1387966] [CDVTimer][intentandnavigationfilter] 10.311961ms
2017-01-23 15:34:13.297 ThaliTest[628:1387966] [CDVTimer][gesturehandler] 0.364006ms
2017-01-23 15:34:13.297 ThaliTest[628:1387966] [CDVTimer][TotalPluginStartup] 14.192998ms
,2017-01-23 15:34:21.197 ThaliTest[628:1387966] Resetting plugins due to page load.
,2017-01-23 15:34:21.959 ThaliTest[628:1387966] Finished load of: file:///var/containers/Bundle/Application/8FAD72A4-94EC-4584-886D-8D845C0789E2/ThaliTest.app/www/index.html
,2017-01-23 15:34:22.415 ThaliTest[628:1387966] JXcore Cordova plugin initializing
2017-01-23 15:34:22.416 ThaliTest[628:1388197] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-23 14:34:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-23 14:34:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-23 14:34:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-23 14:34:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-23 14:34:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-23 14:35:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.56650400161743
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
