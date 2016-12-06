#### Test 9629306271be26a_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9629306271be26a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/6C6F1E80-704C-487E-B0E3-F13E9A94C567/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6C6F1E80-704C-487E-B0E3-F13E9A94C567/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9629306271be26a/build_ios/ThaliTest.app"
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Current executable set to '/Users/thali/Github/CI/builder/builds/9629306271be26a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/22D1CD24-D741-4D68-96E1-25220E0EB45A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54154"
,(lldb)     command script import "/tmp/6C6F1E80-704C-487E-B0E3-F13E9A94C567/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-06 16:44:47.145 ThaliTest[320:139509] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/91A5C3B1-D4BD-46A7-BC69-4627031CB309/Library/Cookies/Cookies.binarycookies
(lldb) ,2016-12-06 16:44:47.543 ThaliTest[320:139509] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-06 16:44:47.545 ThaliTest[320:139509] Multi-tasking -> Device: YES, App: YES
(lldb) ,2016-12-06 16:44:47.565 ThaliTest[320:139509] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-06 16:44:49.822 ThaliTest[320:139509] Using UIWebView
(lldb) ,2016-12-06 16:44:49.829 ThaliTest[320:139509] [CDVTimer][handleopenurl] 0.347018ms
,2016-12-06 16:44:49.836 ThaliTest[320:139509] [CDVTimer][intentandnavigationfilter] 6.322026ms
(lldb) ,2016-12-06 16:44:49.836 ThaliTest[320:139509] [CDVTimer][gesturehandler] 0.275970ms
,2016-12-06 16:44:49.837 ThaliTest[320:139509] [CDVTimer][TotalPluginStartup] 8.426011ms
(lldb) ,2016-12-06 16:44:57.068 ThaliTest[320:139509] Resetting plugins due to page load.
(lldb) ,2016-12-06 16:45:00.617 ThaliTest[320:139509] Finished load of: file:///var/mobile/Containers/Bundle/Application/22D1CD24-D741-4D68-96E1-25220E0EB45A/ThaliTest.app/www/index.html
(lldb) ,2016-12-06 16:45:00.766 ThaliTest[320:139509] JXcore Cordova plugin initializing
,2016-12-06 16:45:00.767 ThaliTest[320:139744] JXcore instance initializing
(lldb) ,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
(lldb) ,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
(lldb) 2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2016-12-06 15:45:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
(lldb) ,Optional(false)
Optional(true)
,2016-12-06 15:45:35 - DEBUG UnitTest_app: 'Running unit tests'
(lldb) ,*Native tests were executed*
,Total number of executed tests:  116
(lldb) ,Number of passed tests:  116
,Number of failed tests:  0
(lldb) ,Number of ignored tests:  0
,Total duration:  25.37023001909256
(lldb) ,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
