#### Test 9781689977f4746_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6A00AA93-04D2-4FE1-8702-58E3A6CAD898/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/6A00AA93-04D2-4FE1-8702-58E3A6CAD898/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F9A1B968-3BE5-47EF-AF60-A3122741C4EB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57058"
,(lldb)     command script import "/tmp/6A00AA93-04D2-4FE1-8702-58E3A6CAD898/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 20:45:40.733 ThaliTest[602:837009] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9690F4FF-769B-4150-B815-0BB67455D0EA/Library/Cookies/Cookies.binarycookies
,2016-12-13 20:45:40.846 ThaliTest[602:837009] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 20:45:40.849 ThaliTest[602:837009] Multi-tasking -> Device: YES, App: YES
,2016-12-13 20:45:40.869 ThaliTest[602:837009] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 20:45:41.335 ThaliTest[602:837009] Using UIWebView
,2016-12-13 20:45:41.343 ThaliTest[602:837009] [CDVTimer][handleopenurl] 0.429988ms
,2016-12-13 20:45:41.354 ThaliTest[602:837009] [CDVTimer][intentandnavigationfilter] 10.456026ms
2016-12-13 20:45:41.355 ThaliTest[602:837009] [CDVTimer][gesturehandler] 0.355959ms
2016-12-13 20:45:41.355 ThaliTest[602:837009] [CDVTimer][TotalPluginStartu,p] 13.202012ms
,2016-12-13 20:45:47.176 ThaliTest[602:837009] Resetting plugins due to page load.
,2016-12-13 20:45:47.609 ThaliTest[602:837009] Finished load of: file:///var/containers/Bundle/Application/F9A1B968-3BE5-47EF-AF60-A3122741C4EB/ThaliTest.app/www/index.html
,2016-12-13 20:45:48.000 ThaliTest[602:837009] JXcore Cordova plugin initializing
,2016-12-13 20:45:48.001 ThaliTest[602:837190] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 19:46:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 19:46:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 19:46:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 19:46:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 19:46:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 19:46:25 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.20729601383209
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
