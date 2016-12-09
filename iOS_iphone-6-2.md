#### Test 9728853323bc6d7_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/715AA6FF-B322-4D33-8C7F-3D4F30FA0003/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/715AA6FF-B322-4D33-8C7F-3D4F30FA0003/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C46335A2-EE4B-4546-A891-0D94F03FA425/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59442"
,(lldb)     command script import "/tmp/715AA6FF-B322-4D33-8C7F-3D4F30FA0003/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-09 12:20:09.161 ThaliTest[431:332422] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F61CD55-5C13-40C9-8A99-443B7B673C6D/Library/Cookies/Cookies.binarycookies
,2016-12-09 12:20:09.204 ThaliTest[431:332422] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-09 12:20:09.205 ThaliTest[431:332422] Multi-tasking -> Device: YES, App: YES
,2016-12-09 12:20:09.217 ThaliTest[431:332422] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-09 12:20:09.536 ThaliTest[431:332422] Using UIWebView
2016-12-09 12:20:09.539 ThaliTest[431:332422] [CDVTimer][handleopenurl] 0.168979ms
,2016-12-09 12:20:09.544 ThaliTest[431:332422] [CDVTimer][intentandnavigationfilter] 4.645944ms
2016-12-09 12:20:09.544 ThaliTest[431:332422] [CDVTimer][gesturehandler] 0.155032ms
2016-12-09 12:20:09.545 ThaliTest[431:332422] [CDVTimer][TotalPluginStartup,] 5.730033ms
,2016-12-09 12:20:15.479 ThaliTest[431:332422] Resetting plugins due to page load.
,2016-12-09 12:20:15.816 ThaliTest[431:332422] Finished load of: file:///var/containers/Bundle/Application/C46335A2-EE4B-4546-A891-0D94F03FA425/ThaliTest.app/www/index.html
,2016-12-09 12:20:16.151 ThaliTest[431:332422] JXcore Cordova plugin initializing
2016-12-09 12:20:16.152 ThaliTest[431:332641] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-09 11:20:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-09 11:20:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-09 11:20:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-09 11:20:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-09 11:20:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-09 11:20:51 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.13657200336456
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
