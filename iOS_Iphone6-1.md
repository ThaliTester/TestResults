#### Test 81444731251ddd8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/144BA4DA-1371-4ECB-A375-5A1062C0351F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/144BA4DA-1371-4ECB-A375-5A1062C0351F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E90A175E-8B32-460D-B5FC-4A4F97B4FB1C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56006"
,(lldb)     command script import "/tmp/144BA4DA-1371-4ECB-A375-5A1062C0351F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 19:01:22.561 ThaliTest[577:608321] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/559C96A3-31E8-4761-9E7A-ABDA118C6AD6/Library/Cookies/Cookies.binarycookies
,2016-08-26 19:01:23.003 ThaliTest[577:608321] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 19:01:23.005 ThaliTest[577:608321] Multi-tasking -> Device: YES, App: YES
,2016-08-26 19:01:23.031 ThaliTest[577:608321] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 19:01:24.813 ThaliTest[577:608321] Using UIWebView
,2016-08-26 19:01:24.821 ThaliTest[577:608321] [CDVTimer][handleopenurl] 0.435948ms
,2016-08-26 19:01:24.829 ThaliTest[577:608321] [CDVTimer][intentandnavigationfilter] 7.331967ms
2016-08-26 19:01:24.829 ThaliTest[577:608321] [CDVTimer][gesturehandler] 0.348985ms
2016-08-26 19:01:24.830 ThaliTest[577:608321] [CDVTimer][TotalPluginStartup] 10.089993ms
,2016-08-26 19:01:30.701 ThaliTest[577:608321] Resetting plugins due to page load.
,2016-08-26 19:01:33.567 ThaliTest[577:608321] Finished load of: file:///var/mobile/Containers/Bundle/Application/E90A175E-8B32-460D-B5FC-4A4F97B4FB1C/ThaliTest.app/www/index.html
,2016-08-26 19:01:33.800 ThaliTest[577:608321] JXcore Cordova plugin initializing
,2016-08-26 19:01:33.801 ThaliTest[577:608582] JXcore instance initializing
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
,Number of passed tests:  15
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.33971095085144
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
