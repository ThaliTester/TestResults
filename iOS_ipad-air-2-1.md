#### Test 962930626a8dc4e_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/962930626a8dc4e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/EA2A681C-B692-46F5-B828-3FDE4C25E2CC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EA2A681C-B692-46F5-B828-3FDE4C25E2CC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/962930626a8dc4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/962930626a8dc4e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A1FC15DC-EE45-4DBC-AC46-BC24FE7074E3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55807"
,(lldb)     command script import "/tmp/EA2A681C-B692-46F5-B828-3FDE4C25E2CC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-06 17:32:27.206 ThaliTest[328:144802] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4DB075B4-D080-4707-98B6-19D9CD5184BC/Library/Cookies/Cookies.binarycookies
(lldb) ,2016-12-06 17:32:27.540 ThaliTest[328:144802] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-06 17:32:27.541 ThaliTest[328:144802] Multi-tasking -> Device: YES, App: YES
(lldb) ,2016-12-06 17:32:27.560 ThaliTest[328:144802] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

(lldb) ,2016-12-06 17:32:29.715 ThaliTest[328:144802] Using UIWebView
(lldb) ,2016-12-06 17:32:29.722 ThaliTest[328:144802] [CDVTimer][handleopenurl] 0.352979ms
(lldb) ,2016-12-06 17:32:29.730 ThaliTest[328:144802] [CDVTimer][intentandnavigationfilter] 7.006049ms
,2016-12-06 17:32:29.731 ThaliTest[328:144802] [CDVTimer][gesturehandler] 0.322998ms
(lldb) ,2016-12-06 17:32:29.731 ThaliTest[328:144802] [CDVTimer][TotalPluginStartup] 9.353042ms
,2016-12-06 17:32:36.630 ThaliTest[328:144802] Resetting plugins due to page load.
(lldb) ,2016-12-06 17:32:40.462 ThaliTest[328:144802] Finished load of: file:///var/mobile/Containers/Bundle/Application/A1FC15DC-EE45-4DBC-AC46-BC24FE7074E3/ThaliTest.app/www/index.html
(lldb) ,2016-12-06 17:32:40.475 ThaliTest[328:144802] JXcore Cordova plugin initializing
,2016-12-06 17:32:40.476 ThaliTest[328:145036] JXcore instance initializing
(lldb) ,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
(lldb) ,Platform ios
Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
,JXcore engine is started
(lldb) ,2016-12-06 16:32:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2016-12-06 16:32:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-06 16:32:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-06 16:32:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2016-12-06 16:32:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,Optional(true)
Optional(false)
(lldb) ,Optional(false)
Optional(true)
,2016-12-06 16:33:16 - DEBUG UnitTest_app: 'Running unit tests'
(lldb) ,*Native tests were executed*
,Total number of executed tests:  116
(lldb) ,Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  26.10074204206467
(lldb) ,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
