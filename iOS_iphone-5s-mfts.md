#### Test 9728853323bc6d7_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4A39D708-2B87-4ADF-8325-1330677045DA/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/4A39D708-2B87-4ADF-8325-1330677045DA/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9296E26C-1925-4729-BAA0-EA973CE61039/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59444"
,(lldb)     command script import "/tmp/4A39D708-2B87-4ADF-8325-1330677045DA/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-09 12:20:24.004 ThaliTest[442:363892] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9A5F5293-1B09-406E-ABB4-928C6CCF9689/Library/Cookies/Cookies.binarycookies
,2016-12-09 12:20:24.094 ThaliTest[442:363892] Apache Cordova native platform version 4.3.1 is starting.
2016-12-09 12:20:24.096 ThaliTest[442:363892] Multi-tasking -> Device: YES, App: YES
,2016-12-09 12:20:24.117 ThaliTest[442:363892] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-09 12:20:24.543 ThaliTest[442:363892] Using UIWebView
,2016-12-09 12:20:24.549 ThaliTest[442:363892] [CDVTimer][handleopenurl] 0.452995ms
,2016-12-09 12:20:24.557 ThaliTest[442:363892] [CDVTimer][intentandnavigationfilter] 7.315993ms
2016-12-09 12:20:24.558 ThaliTest[442:363892] [CDVTimer][gesturehandler] 0.250995ms
2016-12-09 12:20:24.558 ThaliTest[442:363892] [CDVTimer][TotalPluginStartup] 9.348989ms
,2016-12-09 12:20:32.205 ThaliTest[442:363892] Resetting plugins due to page load.
,2016-12-09 12:20:32.858 ThaliTest[442:363892] Finished load of: file:///var/containers/Bundle/Application/9296E26C-1925-4729-BAA0-EA973CE61039/ThaliTest.app/www/index.html
,2016-12-09 12:20:33.408 ThaliTest[442:363892] JXcore Cordova plugin initializing
,2016-12-09 12:20:33.409 ThaliTest[442:364089] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-09 11:20:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-09 11:20:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-09 11:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-09 11:20:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-09 11:20:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-09 11:21:10 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.15085703134537
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
