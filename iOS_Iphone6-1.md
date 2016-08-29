#### Test 81444731606602a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/67215800-62C0-4015-906A-16C645DAFC1E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/67215800-62C0-4015-906A-16C645DAFC1E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/275660AC-F26F-4D71-8DAD-929A1F221FAA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60432"
,(lldb)     command script import "/tmp/67215800-62C0-4015-906A-16C645DAFC1E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:26:55.787 ThaliTest[736:987629] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C2186D59-8834-445B-9FE7-5CBB735D51F0/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:26:56.235 ThaliTest[736:987629] Apache Cordova native platform version 4.1.1 is starting.
2016-08-29 13:26:56.237 ThaliTest[736:987629] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:26:56.262 ThaliTest[736:987629] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:26:58.002 ThaliTest[736:987629] Using UIWebView
,2016-08-29 13:26:58.009 ThaliTest[736:987629] [CDVTimer][handleopenurl] 0.404954ms
,2016-08-29 13:26:58.017 ThaliTest[736:987629] [CDVTimer][intentandnavigationfilter] 7.117033ms
2016-08-29 13:26:58.017 ThaliTest[736:987629] [CDVTimer][gesturehandler] 0.380993ms
2016-08-29 13:26:58.018 ThaliTest[736:987629] [CDVTimer][TotalPluginStartup] 9.625971ms
,2016-08-29 13:27:04.122 ThaliTest[736:987629] Resetting plugins due to page load.
,2016-08-29 13:27:07.171 ThaliTest[736:987629] Finished load of: file:///var/mobile/Containers/Bundle/Application/275660AC-F26F-4D71-8DAD-929A1F221FAA/ThaliTest.app/www/index.html
,2016-08-29 13:27:07.387 ThaliTest[736:987629] JXcore Cordova plugin initializing
,2016-08-29 13:27:07.387 ThaliTest[736:987850] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
,Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  38.46006995439529
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
