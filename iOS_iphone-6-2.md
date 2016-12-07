#### Test 96524298ae159c7_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/53B2E171-B3C1-4A58-8C0E-A58B6E81B721/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/53B2E171-B3C1-4A58-8C0E-A58B6E81B721/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F69DEE7F-2CC8-4AEC-B3DF-CEE4D3CCF619/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58250"
,(lldb)     command script import "/tmp/53B2E171-B3C1-4A58-8C0E-A58B6E81B721/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 12:07:44.121 ThaliTest[284:111290] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6D206C0D-C224-4335-9D9B-2211124E73C4/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:07:44.158 ThaliTest[284:111290] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:07:44.159 ThaliTest[284:111290] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:07:44.171 ThaliTest[284:111290] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:07:44.846 ThaliTest[284:111290] Using UIWebView
2016-12-07 12:07:44.852 ThaliTest[284:111290] [CDVTimer][handleopenurl] 0.316024ms
,2016-12-07 12:07:44.863 ThaliTest[284:111290] [CDVTimer][intentandnavigationfilter] 10.482967ms
2016-12-07 12:07:44.864 ThaliTest[284:111290] [CDVTimer][gesturehandler] 0.344038ms
2016-12-07 12:07:44.865 ThaliTest[284:111290] [CDVTimer][TotalPluginStartu,p] 12.754977ms
,2016-12-07 12:07:50.788 ThaliTest[284:111290] Resetting plugins due to page load.
,2016-12-07 12:07:51.142 ThaliTest[284:111290] Finished load of: file:///var/containers/Bundle/Application/F69DEE7F-2CC8-4AEC-B3DF-CEE4D3CCF619/ThaliTest.app/www/index.html
,2016-12-07 12:07:51.502 ThaliTest[284:111290] JXcore Cordova plugin initializing
,2016-12-07 12:07:51.503 ThaliTest[284:111501] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 11:08:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:08:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:08:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 11:08:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 11:08:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 11:08:28 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.21491795778275
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
