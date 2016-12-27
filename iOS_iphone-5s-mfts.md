#### Test 99374565145ad70_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99374565145ad70/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/66ED78B0-863F-4997-9109-2C1B328D7B0C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/66ED78B0-863F-4997-9109-2C1B328D7B0C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99374565145ad70/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99374565145ad70/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/33FFDF6C-0827-4526-8E97-6BF18C56267E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58399"
,(lldb)     command script import "/tmp/66ED78B0-863F-4997-9109-2C1B328D7B0C/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 12:06:46.892 ThaliTest[1252:2453161] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/45346EFF-1DE7-425A-8009-2796E64C141A/Library/Cookies/Cookies.binarycookies
,2016-12-27 12:06:46.989 ThaliTest[1252:2453161] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 12:06:46.992 ThaliTest[1252:2453161] Multi-tasking -> Device: YES, App: YES
,2016-12-27 12:06:47.013 ThaliTest[1252:2453161] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 12:06:47.474 ThaliTest[1252:2453161] Using UIWebView
,2016-12-27 12:06:47.482 ThaliTest[1252:2453161] [CDVTimer][handleopenurl] 0.539005ms
,2016-12-27 12:06:47.493 ThaliTest[1252:2453161] [CDVTimer][intentandnavigationfilter] 10.237038ms
2016-12-27 12:06:47.494 ThaliTest[1252:2453161] [CDVTimer][gesturehandler] 0.369966ms
2016-12-27 12:06:47.495 ThaliTest[1252:2453161] [CDVTimer][TotalPlugin,Startup] 13.068020ms
,2016-12-27 12:06:53.235 ThaliTest[1252:2453161] Resetting plugins due to page load.
,2016-12-27 12:06:53.644 ThaliTest[1252:2453161] Finished load of: file:///var/containers/Bundle/Application/33FFDF6C-0827-4526-8E97-6BF18C56267E/ThaliTest.app/www/index.html
,2016-12-27 12:06:54.030 ThaliTest[1252:2453161] JXcore Cordova plugin initializing
,2016-12-27 12:06:54.031 ThaliTest[1252:2453356] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 11:07:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 11:07:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 11:07:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-27 11:07:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 11:07:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 11:07:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.27555197477341
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
