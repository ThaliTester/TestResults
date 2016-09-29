#### Test 8712674671a25ec_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/41D52CCC-DFA3-4AE1-ADD7-B9F593B2EF80/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/41D52CCC-DFA3-4AE1-ADD7-B9F593B2EF80/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/36F5E44C-EA6E-494A-B5C8-6A1A4BC8ED2B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64209"
,(lldb)     command script import "/tmp/41D52CCC-DFA3-4AE1-ADD7-B9F593B2EF80/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 09:40:35.403 ThaliTest[1655:2619876] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B4EAE4E0-E1F3-423E-9127-A93545B0782A/Library/Cookies/Cookies.binarycookies
,2016-09-29 09:40:35.441 ThaliTest[1655:2619876] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 09:40:35.442 ThaliTest[1655:2619876] Multi-tasking -> Device: YES, App: YES
,2016-09-29 09:40:35.453 ThaliTest[1655:2619876] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 09:40:35.741 ThaliTest[1655:2619876] Using UIWebView
,2016-09-29 09:40:35.746 ThaliTest[1655:2619876] [CDVTimer][handleopenurl] 0.187039ms
,2016-09-29 09:40:35.750 ThaliTest[1655:2619876] [CDVTimer][intentandnavigationfilter] 3.544986ms
2016-09-29 09:40:35.750 ThaliTest[1655:2619876] [CDVTimer][gesturehandler] 0.165999ms
2016-09-29 09:40:35.750 ThaliTest[1655:2619876] [CDVTimer][TotalPluginS,tartup] 4.745007ms
,2016-09-29 09:40:40.951 ThaliTest[1655:2619876] Resetting plugins due to page load.
,2016-09-29 09:40:41.303 ThaliTest[1655:2619876] Finished load of: file:///var/containers/Bundle/Application/36F5E44C-EA6E-494A-B5C8-6A1A4BC8ED2B/ThaliTest.app/www/index.html
,2016-09-29 09:40:41.632 ThaliTest[1655:2619876] JXcore Cordova plugin initializing
2016-09-29 09:40:41.632 ThaliTest[1655:2620032] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x140819f10>
,Optional("AEBFF268-22E6-4502-9C07-9270A69E530D")
,nil
,nil
,Optional("DA7BFBAC-0745-4CFA-85FE-CC337F514D68")
,Optional("DABBEE93-035D-41B9-AAD5-F3AC4D5C1DEC")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  13.85803598165512
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
