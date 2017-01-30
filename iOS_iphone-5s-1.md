#### Test 103691986c90445e_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/25648B40-13F5-42CB-9F76-1060A493B683/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/25648B40-13F5-42CB-9F76-1060A493B683/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1BDEB122-D177-4C62-8062-A6E5DE3D331F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54175"
,(lldb)     command script import "/tmp/25648B40-13F5-42CB-9F76-1060A493B683/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-30 09:36:05.855 ThaliTest[3051:7907665] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/880606A4-9017-4DFB-BFB7-B8315B5A5362/Library/Cookies/Cookies.binarycookies
,2017-01-30 09:36:05.961 ThaliTest[3051:7907665] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-30 09:36:05.962 ThaliTest[3051:7907665] Multi-tasking -> Device: YES, App: YES
,2017-01-30 09:36:05.980 ThaliTest[3051:7907665] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-30 09:36:07.713 ThaliTest[3051:7907665] Using UIWebView
,2017-01-30 09:36:07.722 ThaliTest[3051:7907665] [CDVTimer][handleopenurl] 0.445008ms
,2017-01-30 09:36:07.731 ThaliTest[3051:7907665] [CDVTimer][intentandnavigationfilter] 9.294987ms
2017-01-30 09:36:07.732 ThaliTest[3051:7907665] [CDVTimer][gesturehandler] 0.382960ms
2017-01-30 09:36:07.733 ThaliTest[3051:7907665] [CDVTimer][TotalPluginS,tartup] 12.142003ms
,2017-01-30 09:36:13.558 ThaliTest[3051:7907665] Resetting plugins due to page load.
,2017-01-30 09:36:17.180 ThaliTest[3051:7907665] Finished load of: file:///var/mobile/Containers/Bundle/Application/1BDEB122-D177-4C62-8062-A6E5DE3D331F/ThaliTest.app/www/index.html
,2017-01-30 09:36:17.499 ThaliTest[3051:7907665] JXcore Cordova plugin initializing
,2017-01-30 09:36:17.500 ThaliTest[3051:7907885] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-30 08:36:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-30 08:36:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-30 08:36:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-30 08:36:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-30 08:36:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-30 08:36:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.2146509885788
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
