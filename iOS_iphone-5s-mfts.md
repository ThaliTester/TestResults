#### Test 9732732894937d3_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/84F415AB-26ED-4D77-B66A-D4195E1E8D7A/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/84F415AB-26ED-4D77-B66A-D4195E1E8D7A/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DEF175E0-7A0A-4EAF-974D-8E1D54CDCAA0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61909"
,(lldb)     command script import "/tmp/84F415AB-26ED-4D77-B66A-D4195E1E8D7A/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-09 16:50:46.808 ThaliTest[453:386567] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A1485FED-7841-441A-8D4B-996F60606D87/Library/Cookies/Cookies.binarycookies
,2016-12-09 16:50:46.918 ThaliTest[453:386567] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-09 16:50:46.921 ThaliTest[453:386567] Multi-tasking -> Device: YES, App: YES
,2016-12-09 16:50:46.944 ThaliTest[453:386567] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-09 16:50:47.429 ThaliTest[453:386567] Using UIWebView
,2016-12-09 16:50:47.437 ThaliTest[453:386567] [CDVTimer][handleopenurl] 0.551999ms
,2016-12-09 16:50:47.448 ThaliTest[453:386567] [CDVTimer][intentandnavigationfilter] 10.371029ms
2016-12-09 16:50:47.449 ThaliTest[453:386567] [CDVTimer][gesturehandler] 0.364006ms
2016-12-09 16:50:47.449 ThaliTest[453:386567] [CDVTimer][TotalPluginStartu,p] 13.181031ms
,2016-12-09 16:50:54.317 ThaliTest[453:386567] Resetting plugins due to page load.
,2016-12-09 16:50:54.839 ThaliTest[453:386567] Finished load of: file:///var/containers/Bundle/Application/DEF175E0-7A0A-4EAF-974D-8E1D54CDCAA0/ThaliTest.app/www/index.html
,2016-12-09 16:50:55.288 ThaliTest[453:386567] JXcore Cordova plugin initializing
,2016-12-09 16:50:55.289 ThaliTest[453:386743] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-09 15:51:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-09 15:51:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-09 15:51:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-09 15:51:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-09 15:51:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-09 15:51:33 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.79245400428772
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
