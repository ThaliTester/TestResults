#### Test 9629306271be26a_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9629306271be26a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/A8F6E9D5-BC5F-484F-B38A-23918C66C0EA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A8F6E9D5-BC5F-484F-B38A-23918C66C0EA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9629306271be26a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9629306271be26a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EAB5977F-9CC9-4663-AE21-72B61508A160/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54153"
,(lldb)     command script import "/tmp/A8F6E9D5-BC5F-484F-B38A-23918C66C0EA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-06 16:44:45.217 ThaliTest[314:151332] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C9AE7F3-1AD4-4D3B-B31C-25DFE3325319/Library/Cookies/Cookies.binarycookies
(lldb) ,2016-12-06 16:44:45.330 ThaliTest[314:151332] Apache Cordova native platform version 4.3.1 is starting.
(lldb) ,2016-12-06 16:44:45.333 ThaliTest[314:151332] Multi-tasking -> Device: YES, App: YES
,2016-12-06 16:44:45.359 ThaliTest[314:151332] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

(lldb) ,2016-12-06 16:44:47.138 ThaliTest[314:151332] Using UIWebView
(lldb) ,2016-12-06 16:44:47.149 ThaliTest[314:151332] [CDVTimer][handleopenurl] 0.437975ms
,2016-12-06 16:44:47.160 ThaliTest[314:151332] [CDVTimer][intentandnavigationfilter] 10.451019ms
(lldb) ,2016-12-06 16:44:47.162 ThaliTest[314:151332] [CDVTimer][gesturehandler] 0.813007ms
2016-12-06 16:44:47.162 ThaliTest[314:151332] [CDVTimer][TotalPluginStartup] 13.705969ms
,2016-12-06 16:44:54.159 ThaliTest[314:151332] Resetting plugins due to page load.
(lldb) ,2016-12-06 16:44:57.962 ThaliTest[314:151332] Finished load of: file:///var/mobile/Containers/Bundle/Application/EAB5977F-9CC9-4663-AE21-72B61508A160/ThaliTest.app/www/index.html
(lldb) ,2016-12-06 16:44:58.274 ThaliTest[314:151332] JXcore Cordova plugin initializing
(lldb) ,2016-12-06 16:44:58.275 ThaliTest[314:151552] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
(lldb) ,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,Optional(true)
Optional(false)
Optional(false)
Optional(true)
(lldb) ,2016-12-06 15:45:35 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.13726198673248
*(lldb) ,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
(lldb) ,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
(lldb) ,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
(lldb) 
```
