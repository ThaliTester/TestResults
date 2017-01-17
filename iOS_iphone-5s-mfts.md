#### Test 101910573e732e55_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/101910573e732e55/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B17CF072-11C6-45F3-9C20-6A133685A28D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/B17CF072-11C6-45F3-9C20-6A133685A28D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/101910573e732e55/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/101910573e732e55/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1DE7C334-B86A-4008-95DF-0249CE09AEC9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58858"
,(lldb)     command script import "/tmp/B17CF072-11C6-45F3-9C20-6A133685A28D/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-17 19:06:02.766 ThaliTest[365:605357] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/57BC86C3-1BC7-47AB-B6ED-02E71A558AC8/Library/Cookies/Cookies.binarycookies
,2017-01-17 19:06:02.818 ThaliTest[365:605357] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-17 19:06:02.819 ThaliTest[365:605357] Multi-tasking -> Device: YES, App: YES
,2017-01-17 19:06:02.834 ThaliTest[365:605357] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-17 19:06:03.205 ThaliTest[365:605357] Using UIWebView
2017-01-17 19:06:03.210 ThaliTest[365:605357] [CDVTimer][handleopenurl] 0.250995ms
2017-01-17 19:06:03.216 ThaliTest[365:605357] [CDVTimer][intentandnavigationfilter] 5.953014ms
2017-01-17 19:06:03.217 ThaliTest[365:605357] [CDVTimer][gesturehandler] 0.423014ms
2017-01-17 19:06:03.217 ThaliTest[365:605357] [CDVTimer][TotalPluginStartup] 7.770956ms
,2017-01-17 19:06:10.390 ThaliTest[365:605357] Resetting plugins due to page load.
,2017-01-17 19:06:10.834 ThaliTest[365:605357] Finished load of: file:///var/containers/Bundle/Application/1DE7C334-B86A-4008-95DF-0249CE09AEC9/ThaliTest.app/www/index.html
,2017-01-17 19:06:11.308 ThaliTest[365:605357] JXcore Cordova plugin initializing
,2017-01-17 19:06:11.309 ThaliTest[365:605540] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-17 18:06:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-17 18:06:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-17 18:06:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-17 18:06:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-17 18:06:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-17 18:06:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.00261396169662
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
