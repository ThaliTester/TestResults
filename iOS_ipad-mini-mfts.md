#### Test 102585911579949a_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F87CEA99-3091-4090-9D37-FAFDEEFE7673/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/F87CEA99-3091-4090-9D37-FAFDEEFE7673/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/778C11A7-EFC1-4AF3-B959-C788C272BF69/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62945"
,(lldb)     command script import "/tmp/F87CEA99-3091-4090-9D37-FAFDEEFE7673/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-21 16:58:58.407 ThaliTest[1770:6366444] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/214AB64C-DBB2-40BA-B792-85B21C38A177/Library/Cookies/Cookies.binarycookies
,2017-01-21 16:58:58.554 ThaliTest[1770:6366444] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-21 16:58:58.557 ThaliTest[1770:6366444] Multi-tasking -> Device: YES, App: YES
,2017-01-21 16:58:58.580 ThaliTest[1770:6366444] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-21 16:58:59.098 ThaliTest[1770:6366444] Using UIWebView
2017-01-21 16:58:59.104 ThaliTest[1770:6366444] [CDVTimer][handleopenurl] 0.499964ms
,2017-01-21 16:58:59.113 ThaliTest[1770:6366444] [CDVTimer][intentandnavigationfilter] 8.166015ms
2017-01-21 16:58:59.113 ThaliTest[1770:6366444] [CDVTimer][gesturehandler] 0.306964ms
2017-01-21 16:58:59.113 ThaliTest[1770:6366444] [CDVTimer][TotalPluginS,tartup] 10.221004ms
,2017-01-21 16:59:06.016 ThaliTest[1770:6366444] Resetting plugins due to page load.
,2017-01-21 16:59:06.560 ThaliTest[1770:6366444] Finished load of: file:///var/containers/Bundle/Application/778C11A7-EFC1-4AF3-B959-C788C272BF69/ThaliTest.app/www/index.html
,2017-01-21 16:59:06.818 ThaliTest[1770:6366444] JXcore Cordova plugin initializing
2017-01-21 16:59:06.819 ThaliTest[1770:6366589] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-21 15:59:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-21 15:59:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-21 15:59:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-21 15:59:45 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-21 15:59:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-21 16:00:33 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  47.16494101285934
,Failed to execute UT.
,2017-01-21 16:00:33 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
