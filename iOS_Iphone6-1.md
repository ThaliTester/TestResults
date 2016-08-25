#### Test 82728424ebd9a7c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424ebd9a7c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/530DE47B-40C8-42BA-A7E5-3A2131B00772/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/530DE47B-40C8-42BA-A7E5-3A2131B00772/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424ebd9a7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424ebd9a7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/44E3916B-675E-4283-8312-A769BEA341BD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61353"
,(lldb)     command script import "/tmp/530DE47B-40C8-42BA-A7E5-3A2131B00772/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 17:37:55.996 ThaliTest[444:453511] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/84BD3B3F-7F9A-4C58-A89C-CB7E2B53CD45/Library/Cookies/Cookies.binarycookies
,2016-08-25 17:37:56.432 ThaliTest[444:453511] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 17:37:56.434 ThaliTest[444:453511] Multi-tasking -> Device: YES, App: YES
,2016-08-25 17:37:56.459 ThaliTest[444:453511] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 17:37:58.298 ThaliTest[444:453511] Using UIWebView
,2016-08-25 17:37:58.305 ThaliTest[444:453511] [CDVTimer][handleopenurl] 0.391006ms
,2016-08-25 17:37:58.312 ThaliTest[444:453511] [CDVTimer][intentandnavigationfilter] 7.100999ms
2016-08-25 17:37:58.313 ThaliTest[444:453511] [CDVTimer][gesturehandler] 0.326991ms
2016-08-25 17:37:58.313 ThaliTest[444:453511] [CDVTimer][TotalPluginStartup] 9.454966ms
,2016-08-25 17:38:04.627 ThaliTest[444:453511] Resetting plugins due to page load.
,2016-08-25 17:38:07.875 ThaliTest[444:453511] Finished load of: file:///var/mobile/Containers/Bundle/Application/44E3916B-675E-4283-8312-A769BEA341BD/ThaliTest.app/www/index.html
,2016-08-25 17:38:08.101 ThaliTest[444:453511] JXcore Cordova plugin initializing
2016-08-25 17:38:08.102 ThaliTest[444:453750] JXcore instance initializing
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
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
