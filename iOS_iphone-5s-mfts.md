#### Test 953210620aa0610_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AB0846FF-5569-452B-B65E-03F5F9083F92/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/AB0846FF-5569-452B-B65E-03F5F9083F92/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5708D1BF-3D34-4D1F-AA31-3FF6305A3DCD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54847"
,(lldb)     command script import "/tmp/AB0846FF-5569-452B-B65E-03F5F9083F92/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 16:47:16.080 ThaliTest[356:158121] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F1EE41A-CDC6-455C-BB94-39D31735FEA4/Library/Cookies/Cookies.binarycookies
,2016-12-07 16:47:16.187 ThaliTest[356:158121] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 16:47:16.191 ThaliTest[356:158121] Multi-tasking -> Device: YES, App: YES
,2016-12-07 16:47:16.219 ThaliTest[356:158121] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 16:47:16.636 ThaliTest[356:158121] Using UIWebView
,2016-12-07 16:47:16.645 ThaliTest[356:158121] [CDVTimer][handleopenurl] 0.441015ms
,2016-12-07 16:47:16.655 ThaliTest[356:158121] [CDVTimer][intentandnavigationfilter] 10.210991ms
2016-12-07 16:47:16.656 ThaliTest[356:158121] [CDVTimer][gesturehandler] 0.356019ms
2016-12-07 16:47:16.657 ThaliTest[356:158121] [CDVTimer][TotalPluginStartup] 12.951970ms
,2016-12-07 16:47:22.854 ThaliTest[356:158121] Resetting plugins due to page load.
,2016-12-07 16:47:23.183 ThaliTest[356:158121] Finished load of: file:///var/containers/Bundle/Application/5708D1BF-3D34-4D1F-AA31-3FF6305A3DCD/ThaliTest.app/www/index.html
,2016-12-07 16:47:23.580 ThaliTest[356:158121] JXcore Cordova plugin initializing
,2016-12-07 16:47:23.581 ThaliTest[356:158335] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 15:47:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 15:47:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 15:47:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 15:47:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 15:47:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 15:48:01 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.90473699569702
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
