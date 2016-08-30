#### Test 82914073a71b108_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a71b108/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1962069D-73B5-4DA0-878B-D1C9511BD0CC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1962069D-73B5-4DA0-878B-D1C9511BD0CC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a71b108/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a71b108/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CEBD2651-98F3-44F4-B983-1395F9F9093D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59584"
,(lldb)     command script import "/tmp/1962069D-73B5-4DA0-878B-D1C9511BD0CC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 14:39:20.039 ThaliTest[817:1138227] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E7F295D1-A0EB-44C0-B2E8-9030D9A8E0D0/Library/Cookies/Cookies.binarycookies
,2016-08-30 14:39:20.432 ThaliTest[817:1138227] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 14:39:20.433 ThaliTest[817:1138227] Multi-tasking -> Device: YES, App: YES
,2016-08-30 14:39:20.457 ThaliTest[817:1138227] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 14:39:22.195 ThaliTest[817:1138227] Using UIWebView
,2016-08-30 14:39:22.201 ThaliTest[817:1138227] [CDVTimer][handleopenurl] 0.411034ms
,2016-08-30 14:39:22.210 ThaliTest[817:1138227] [CDVTimer][intentandnavigationfilter] 7.629991ms
2016-08-30 14:39:22.210 ThaliTest[817:1138227] [CDVTimer][gesturehandler] 0.329018ms
2016-08-30 14:39:22.211 ThaliTest[817:1138227] [CDVTimer][TotalPluginStartup] 10.021985ms
,2016-08-30 14:39:28.149 ThaliTest[817:1138227] Resetting plugins due to page load.
,2016-08-30 14:39:30.735 ThaliTest[817:1138227] Finished load of: file:///var/mobile/Containers/Bundle/Application/CEBD2651-98F3-44F4-B983-1395F9F9093D/ThaliTest.app/www/index.html
,2016-08-30 14:39:30.960 ThaliTest[817:1138227] JXcore Cordova plugin initializing
2016-08-30 14:39:30.961 ThaliTest[817:1138454] JXcore instance initializing
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
Total number of executed tests:  21
Number of passed tests:  21
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  43.33381497859955
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
