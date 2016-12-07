#### Test 965327534acc906_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/02AF4608-132E-4F9D-982A-A643AC9C91C7/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/02AF4608-132E-4F9D-982A-A643AC9C91C7/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E1521C37-D594-476A-BFB4-55F73FCFAF9B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62987"
,(lldb)     command script import "/tmp/02AF4608-132E-4F9D-982A-A643AC9C91C7/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 14:16:07.779 ThaliTest[321:141395] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/616381A0-0B62-428C-B700-7FA9638D527B/Library/Cookies/Cookies.binarycookies
,2016-12-07 14:16:07.829 ThaliTest[321:141395] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 14:16:07.831 ThaliTest[321:141395] Multi-tasking -> Device: YES, App: YES
,2016-12-07 14:16:07.846 ThaliTest[321:141395] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 14:16:08.195 ThaliTest[321:141395] Using UIWebView
,2016-12-07 14:16:08.199 ThaliTest[321:141395] [CDVTimer][handleopenurl] 0.304997ms
,2016-12-07 14:16:08.204 ThaliTest[321:141395] [CDVTimer][intentandnavigationfilter] 4.752994ms
2016-12-07 14:16:08.205 ThaliTest[321:141395] [CDVTimer][gesturehandler] 0.191987ms
2016-12-07 14:16:08.205 ThaliTest[321:141395] [CDVTimer][TotalPluginStartup,] 6.258011ms
,2016-12-07 14:16:14.348 ThaliTest[321:141395] Resetting plugins due to page load.
,2016-12-07 14:16:14.732 ThaliTest[321:141395] Finished load of: file:///var/containers/Bundle/Application/E1521C37-D594-476A-BFB4-55F73FCFAF9B/ThaliTest.app/www/index.html
,2016-12-07 14:16:15.128 ThaliTest[321:141395] JXcore Cordova plugin initializing
,2016-12-07 14:16:15.129 ThaliTest[321:141598] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 13:16:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 13:16:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 13:16:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 13:16:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 13:16:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser's mock node client received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 13:16:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  30.45013296604156
Failed to execute UT.
,2016-12-07 13:16:58 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
