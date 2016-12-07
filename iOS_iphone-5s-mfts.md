#### Test 95321062fff4ed0_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C4E733D5-315A-48F4-80BF-1F27A5B901AF/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/C4E733D5-315A-48F4-80BF-1F27A5B901AF/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/85A15CB3-FC58-4B92-9CF5-CB07CE65F66B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57311"
,(lldb)     command script import "/tmp/C4E733D5-315A-48F4-80BF-1F27A5B901AF/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 18:31:58.570 ThaliTest[372:167873] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/606C96D6-2830-4C92-AEE5-5679AF599B10/Library/Cookies/Cookies.binarycookies
,2016-12-07 18:31:58.659 ThaliTest[372:167873] Apache Cordova native platform version 4.3.1 is starting.
2016-12-07 18:31:58.661 ThaliTest[372:167873] Multi-tasking -> Device: YES, App: YES
,2016-12-07 18:31:58.681 ThaliTest[372:167873] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 18:31:59.170 ThaliTest[372:167873] Using UIWebView
,2016-12-07 18:31:59.178 ThaliTest[372:167873] [CDVTimer][handleopenurl] 0.551999ms
,2016-12-07 18:31:59.189 ThaliTest[372:167873] [CDVTimer][intentandnavigationfilter] 10.506988ms
2016-12-07 18:31:59.190 ThaliTest[372:167873] [CDVTimer][gesturehandler] 0.356972ms
2016-12-07 18:31:59.191 ThaliTest[372:167873] [CDVTimer][TotalPluginStartu,p] 13.334036ms
,2016-12-07 18:32:05.259 ThaliTest[372:167873] Resetting plugins due to page load.
,2016-12-07 18:32:05.760 ThaliTest[372:167873] Finished load of: file:///var/containers/Bundle/Application/85A15CB3-FC58-4B92-9CF5-CB07CE65F66B/ThaliTest.app/www/index.html
,2016-12-07 18:32:06.272 ThaliTest[372:167873] JXcore Cordova plugin initializing
,2016-12-07 18:32:06.273 ThaliTest[372:168050] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 17:32:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 17:32:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 17:32:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 17:32:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 17:32:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,failed - Unexpected connect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 39
,2016-12-07 17:32:44 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  25.1221079826355
Failed to execute UT.
,2016-12-07 17:32:44 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
