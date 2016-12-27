#### Test 9945185497797f9_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9945185497797f9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/987BE5AC-F699-4B31-8541-561153BA7807/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/987BE5AC-F699-4B31-8541-561153BA7807/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9945185497797f9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9945185497797f9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/74B9AD38-4C0E-4C1D-B827-659F5B14F28E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53691"
,(lldb)     command script import "/tmp/987BE5AC-F699-4B31-8541-561153BA7807/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 16:20:11.735 ThaliTest[1439:2559442] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D4DC21A1-EEC1-4940-852E-D1B0134DCB1F/Library/Cookies/Cookies.binarycookies
,2016-12-27 16:20:11.813 ThaliTest[1439:2559442] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 16:20:11.815 ThaliTest[1439:2559442] Multi-tasking -> Device: YES, App: YES
,2016-12-27 16:20:11.837 ThaliTest[1439:2559442] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 16:20:12.225 ThaliTest[1439:2559442] Using UIWebView
,2016-12-27 16:20:12.230 ThaliTest[1439:2559442] [CDVTimer][handleopenurl] 0.330985ms
,2016-12-27 16:20:12.236 ThaliTest[1439:2559442] [CDVTimer][intentandnavigationfilter] 5.842030ms
2016-12-27 16:20:12.237 ThaliTest[1439:2559442] [CDVTimer][gesturehandler] 0.200987ms
2016-12-27 16:20:12.237 ThaliTest[1439:2559442] [CDVTimer][TotalPluginStartup] 7.472038ms
,2016-12-27 16:20:18.075 ThaliTest[1439:2559442] Resetting plugins due to page load.
,2016-12-27 16:20:18.352 ThaliTest[1439:2559442] Finished load of: file:///var/containers/Bundle/Application/74B9AD38-4C0E-4C1D-B827-659F5B14F28E/ThaliTest.app/www/index.html
,2016-12-27 16:20:18.719 ThaliTest[1439:2559442] JXcore Cordova plugin initializing
,2016-12-27 16:20:18.720 ThaliTest[1439:2559630] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 15:20:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 15:20:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 15:20:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-27 15:20:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 15:20:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-27 15:20:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  27.06463003158569
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
