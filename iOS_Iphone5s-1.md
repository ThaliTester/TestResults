#### Test 896247961682436_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247961682436/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/314BEE5F-90C9-4D40-8AC0-41799CB1A0E6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/314BEE5F-90C9-4D40-8AC0-41799CB1A0E6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247961682436/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247961682436/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CE6D40C1-ACB0-4B18-BEB6-E9B2596EC231/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51549"
,(lldb)     command script import "/tmp/314BEE5F-90C9-4D40-8AC0-41799CB1A0E6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 17:09:15.648 ThaliTest[5350:13514305] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68ED087F-98E8-4652-927B-05B73F252F49/Library/Cookies/Cookies.binarycookies
,2016-11-08 17:09:15.754 ThaliTest[5350:13514305] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 17:09:15.755 ThaliTest[5350:13514305] Multi-tasking -> Device: YES, App: YES
,2016-11-08 17:09:15.776 ThaliTest[5350:13514305] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 17:09:17.210 ThaliTest[5350:13514305] Using UIWebView
,2016-11-08 17:09:17.219 ThaliTest[5350:13514305] [CDVTimer][handleopenurl] 0.620961ms
,2016-11-08 17:09:17.227 ThaliTest[5350:13514305] [CDVTimer][intentandnavigationfilter] 8.204997ms
2016-11-08 17:09:17.228 ThaliTest[5350:13514305] [CDVTimer][gesturehandler] 0.404000ms
2016-11-08 17:09:17.229 ThaliTest[5350:13514305] [CDVTimer][TotalPluginStartup] 11.125028ms
,2016-11-08 17:09:22.891 ThaliTest[5350:13514305] Resetting plugins due to page load.
,2016-11-08 17:09:26.416 ThaliTest[5350:13514305] Finished load of: file:///var/mobile/Containers/Bundle/Application/CE6D40C1-ACB0-4B18-BEB6-E9B2596EC231/ThaliTest.app/www/index.html
,2016-11-08 17:09:26.731 ThaliTest[5350:13514305] JXcore Cordova plugin initializing
,2016-11-08 17:09:26.732 ThaliTest[5350:13514532] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 16:09:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 16:09:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 16:09:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-08 16:09:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 16:09:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-08 16:10:06 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  27.18962901830673
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
