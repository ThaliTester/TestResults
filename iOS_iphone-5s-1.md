#### Test 96524298ae159c7_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/7EDDC3C0-EEDB-4F7D-9739-7D57701648B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7EDDC3C0-EEDB-4F7D-9739-7D57701648B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F0408FCB-D7B4-42A2-B287-8295480148D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58133"
,(lldb)     command script import "/tmp/7EDDC3C0-EEDB-4F7D-9739-7D57701648B0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 12:07:33.241 ThaliTest[367:261189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F7B4B8F-FE54-4BEF-8265-986A97E82AE6/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:07:33.361 ThaliTest[367:261189] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:07:33.362 ThaliTest[367:261189] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:07:33.384 ThaliTest[367:261189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:07:35.055 ThaliTest[367:261189] Using UIWebView
,2016-12-07 12:07:35.063 ThaliTest[367:261189] [CDVTimer][handleopenurl] 0.474989ms
,2016-12-07 12:07:35.074 ThaliTest[367:261189] [CDVTimer][intentandnavigationfilter] 10.295987ms
,2016-12-07 12:07:35.075 ThaliTest[367:261189] [CDVTimer][gesturehandler] 0.782967ms
2016-12-07 12:07:35.076 ThaliTest[367:261189] [CDVTimer][TotalPluginStartup] 13.729036ms
,2016-12-07 12:07:40.921 ThaliTest[367:261189] Resetting plugins due to page load.
,2016-12-07 12:07:44.244 ThaliTest[367:261189] Finished load of: file:///var/mobile/Containers/Bundle/Application/F0408FCB-D7B4-42A2-B287-8295480148D3/ThaliTest.app/www/index.html
,2016-12-07 12:07:44.558 ThaliTest[367:261189] JXcore Cordova plugin initializing
,2016-12-07 12:07:44.560 ThaliTest[367:261495] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 11:07:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:07:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:07:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-07 11:07:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 11:07:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 11:08:22 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.72801601886749
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
