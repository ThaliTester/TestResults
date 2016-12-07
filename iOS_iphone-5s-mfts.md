#### Test 96524298ae159c7_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/365E0590-533A-47F9-B86A-E2CFD40E4613/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/365E0590-533A-47F9-B86A-E2CFD40E4613/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2DA14330-72C7-40B8-B552-AEF6FD96000E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58280"
,(lldb)     command script import "/tmp/365E0590-533A-47F9-B86A-E2CFD40E4613/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 12:07:46.309 ThaliTest[294:125863] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0E00CC14-86A7-4DC7-BA8D-154EDC57F6EF/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:07:46.439 ThaliTest[294:125863] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:07:46.442 ThaliTest[294:125863] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:07:46.484 ThaliTest[294:125863] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:07:46.975 ThaliTest[294:125863] Using UIWebView
,2016-12-07 12:07:46.989 ThaliTest[294:125863] [CDVTimer][handleopenurl] 0.414968ms
,2016-12-07 12:07:47.000 ThaliTest[294:125863] [CDVTimer][intentandnavigationfilter] 11.125982ms
2016-12-07 12:07:47.001 ThaliTest[294:125863] [CDVTimer][gesturehandler] 0.405014ms
2016-12-07 12:07:47.002 ThaliTest[294:125863] [CDVTimer][TotalPluginStartu,p] 13.884008ms
,2016-12-07 12:07:53.295 ThaliTest[294:125863] Resetting plugins due to page load.
,2016-12-07 12:07:53.730 ThaliTest[294:125863] Finished load of: file:///var/containers/Bundle/Application/2DA14330-72C7-40B8-B552-AEF6FD96000E/ThaliTest.app/www/index.html
,2016-12-07 12:07:54.168 ThaliTest[294:125863] JXcore Cordova plugin initializing
,2016-12-07 12:07:54.169 ThaliTest[294:126074] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 11:08:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:08:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:08:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 11:08:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 11:08:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 11:08:32 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.87498897314072
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
