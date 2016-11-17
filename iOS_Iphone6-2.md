#### Test 9357216729ac2d0_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/7C68F376-3FC5-45C8-9974-211901F31852/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/7C68F376-3FC5-45C8-9974-211901F31852/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/426C0702-9D82-481D-89F9-6B2CD8EFAF69/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52316"
,(lldb)     command script import "/tmp/7C68F376-3FC5-45C8-9974-211901F31852/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-11-17 03:16:41.084 ThaliTest[3614:8175646] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2691AC4E-0921-462F-8DF2-343F47E9C252/Library/Cookies/Cookies.binarycookies
,2016-11-17 03:16:41.165 ThaliTest[3614:8175646] Apache Cordova native platform version 4.2.1 is starting.
2016-11-17 03:16:41.167 ThaliTest[3614:8175646] Multi-tasking -> Device: YES, App: YES
,2016-11-17 03:16:41.186 ThaliTest[3614:8175646] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 03:16:41.686 ThaliTest[3614:8175646] Using UIWebView
,2016-11-17 03:16:41.696 ThaliTest[3614:8175646] [CDVTimer][handleopenurl] 0.406981ms
,2016-11-17 03:16:41.704 ThaliTest[3614:8175646] [CDVTimer][intentandnavigationfilter] 6.932020ms
2016-11-17 03:16:41.704 ThaliTest[3614:8175646] [CDVTimer][gesturehandler] 0.268996ms
2016-11-17 03:16:41.705 ThaliTest[3614:8175646] [CDVTimer][TotalPluginS,tartup] 9.216011ms
,2016-11-17 03:16:47.735 ThaliTest[3614:8175646] Resetting plugins due to page load.
,2016-11-17 03:16:48.086 ThaliTest[3614:8175646] Finished load of: file:///var/containers/Bundle/Application/426C0702-9D82-481D-89F9-6B2CD8EFAF69/ThaliTest.app/www/index.html
,2016-11-17 03:16:48.434 ThaliTest[3614:8175646] JXcore Cordova plugin initializing
,2016-11-17 03:16:48.435 ThaliTest[3614:8175809] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 11:16:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 11:16:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 11:16:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 11:16:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 11:16:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,2016-11-17 11:17:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  42.51489698886871
F,ailed to execute UT.
2016-11-17 11:17:41 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
```
