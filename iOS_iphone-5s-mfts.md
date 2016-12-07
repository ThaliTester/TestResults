#### Test 96293062c9b8e19_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5FDC354C-3ACD-4256-A510-C18840865FB4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/5FDC354C-3ACD-4256-A510-C18840865FB4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A6AF3F18-BFA6-4C28-A9AE-0C260D2C6C35/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55670"
,(lldb)     command script import "/tmp/5FDC354C-3ACD-4256-A510-C18840865FB4/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 17:12:41.754 ThaliTest[364:161225] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E96C521C-E7EC-49CA-83FF-416A96363BB2/Library/Cookies/Cookies.binarycookies
,2016-12-07 17:12:41.806 ThaliTest[364:161225] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 17:12:41.807 ThaliTest[364:161225] Multi-tasking -> Device: YES, App: YES
,2016-12-07 17:12:41.823 ThaliTest[364:161225] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 17:12:42.162 ThaliTest[364:161225] Using UIWebView
,2016-12-07 17:12:42.167 ThaliTest[364:161225] [CDVTimer][handleopenurl] 0.315964ms
,2016-12-07 17:12:42.174 ThaliTest[364:161225] [CDVTimer][intentandnavigationfilter] 6.108999ms
2016-12-07 17:12:42.174 ThaliTest[364:161225] [CDVTimer][gesturehandler] 0.189006ms
2016-12-07 17:12:42.175 ThaliTest[364:161225] [CDVTimer][TotalPluginStartup,] 7.637024ms
,2016-12-07 17:12:49.866 ThaliTest[364:161225] Resetting plugins due to page load.
,2016-12-07 17:12:50.585 ThaliTest[364:161225] Finished load of: file:///var/containers/Bundle/Application/A6AF3F18-BFA6-4C28-A9AE-0C260D2C6C35/ThaliTest.app/www/index.html
,2016-12-07 17:12:51.021 ThaliTest[364:161225] JXcore Cordova plugin initializing
,2016-12-07 17:12:51.021 ThaliTest[364:161407] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 16:13:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 16:13:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 16:13:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 16:13:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 16:13:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 16:13:28 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.30736994743347
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
