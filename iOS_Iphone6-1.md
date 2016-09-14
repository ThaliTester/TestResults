#### Test 82914073fb4f932_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B3BD23B9-F031-44F6-B138-FAFF766894D9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B3BD23B9-F031-44F6-B138-FAFF766894D9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1FDFCA70-A4F2-44F2-B211-4C0FF8593C2F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61817"
,(lldb)     command script import "/tmp/B3BD23B9-F031-44F6-B138-FAFF766894D9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 19:24:24.335 ThaliTest[606:759132] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3FCBD99-0FED-4D74-9022-7AFEAD9B7FE2/Library/Cookies/Cookies.binarycookies
,2016-09-14 19:24:24.374 ThaliTest[606:759132] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 19:24:24.375 ThaliTest[606:759132] Multi-tasking -> Device: YES, App: YES
,2016-09-14 19:24:24.386 ThaliTest[606:759132] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 19:24:24.721 ThaliTest[606:759132] Using UIWebView
,2016-09-14 19:24:24.725 ThaliTest[606:759132] [CDVTimer][handleopenurl] 0.216007ms
,2016-09-14 19:24:24.730 ThaliTest[606:759132] [CDVTimer][intentandnavigationfilter] 3.939033ms
2016-09-14 19:24:24.730 ThaliTest[606:759132] [CDVTimer][gesturehandler] 0.150979ms
2016-09-14 19:24:24.730 ThaliTest[606:759132] [CDVTimer][TotalPluginStartup] 5.253971ms
,2016-09-14 19:24:30.214 ThaliTest[606:759132] Resetting plugins due to page load.
,2016-09-14 19:24:30.544 ThaliTest[606:759132] Finished load of: file:///var/containers/Bundle/Application/1FDFCA70-A4F2-44F2-B211-4C0FF8593C2F/ThaliTest.app/www/index.html
,2016-09-14 19:24:30.886 ThaliTest[606:759132] JXcore Cordova plugin initializing
,2016-09-14 19:24:30.887 ThaliTest[606:759318] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 19:24:38.410 ThaliTest[606:759132] BTM: attaching to BTServer
,2016-09-14 19:24:42.999 ThaliTest[606:759132] BTM: local device power state changed
,2016-09-14 19:24:42.999 ThaliTest[606:759132] BTM: power is now off
,2016-09-14 19:24:43.753 ThaliTest[606:759132] BTM: local device power state changed
2016-09-14 19:24:43.754 ThaliTest[606:759132] BTM: power is now on
,received session: <ThaliCore.Session: 0x12f46b020>
,*Native tests were executed*
Total number of executed tests:  48
,Number of passed tests:  48
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  17.3776850104332
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
