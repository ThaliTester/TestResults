#### Test 962930626a8dc4e_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/962930626a8dc4e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/17AF026A-958E-4D1B-8129-4D7608123070/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/17AF026A-958E-4D1B-8129-4D7608123070/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/962930626a8dc4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/962930626a8dc4e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/131E1790-9828-4880-A94A-0BE9EE4F6BF9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55806"
,(lldb)     command script import "/tmp/17AF026A-958E-4D1B-8129-4D7608123070/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-06 17:32:26.173 ThaliTest[324:157106] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/17D38734-DC44-46AD-BF84-7DEDFB63280F/Library/Cookies/Cookies.binarycookies
(lldb) ,2016-12-06 17:32:26.302 ThaliTest[324:157106] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-06 17:32:26.303 ThaliTest[324:157106] Multi-tasking -> Device: YES, App: YES
(lldb) ,2016-12-06 17:32:26.329 ThaliTest[324:157106] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

(lldb) ,2016-12-06 17:32:28.190 ThaliTest[324:157106] Using UIWebView
,2016-12-06 17:32:28.198 ThaliTest[324:157106] [CDVTimer][handleopenurl] 0.431001ms
(lldb) ,2016-12-06 17:32:28.209 ThaliTest[324:157106] [CDVTimer][intentandnavigationfilter] 10.286987ms
2016-12-06 17:32:28.210 ThaliTest[324:157106] [CDVTimer][gesturehandler] 0.424027ms
2016-12-06 17:32:28.211 ThaliTest[324:157106] [CDVTimer][TotalPluginStartu,p] 13.117969ms
(lldb) ,2016-12-06 17:32:34.984 ThaliTest[324:157106] Resetting plugins due to page load.
(lldb) ,2016-12-06 17:32:38.683 ThaliTest[324:157106] Finished load of: file:///var/mobile/Containers/Bundle/Application/131E1790-9828-4880-A94A-0BE9EE4F6BF9/ThaliTest.app/www/index.html
(lldb) ,2016-12-06 17:32:38.998 ThaliTest[324:157106] JXcore Cordova plugin initializing
,2016-12-06 17:32:38.999 ThaliTest[324:157370] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2016-12-06 16:32:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2016-12-06 16:32:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-06 16:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-06 16:32:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2016-12-06 16:32:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
(lldb) ,2016-12-06 16:33:16 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.85496199131012
*(lldb) ,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
(lldb) ,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
(lldb) 
```
