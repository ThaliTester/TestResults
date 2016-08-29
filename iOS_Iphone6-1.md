#### Test 83070177977a8d1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B0E5E550-5299-4140-89B5-92B84B4AD903/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B0E5E550-5299-4140-89B5-92B84B4AD903/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/060E89AE-C3B4-4447-9C26-7184CF969FAC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61922"
,(lldb)     command script import "/tmp/B0E5E550-5299-4140-89B5-92B84B4AD903/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:43:02.574 ThaliTest[744:990099] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32650FC8-B0EC-40C5-AEFA-77A585A2824A/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:43:03.046 ThaliTest[744:990099] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 13:43:03.048 ThaliTest[744:990099] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:43:03.069 ThaliTest[744:990099] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:43:04.801 ThaliTest[744:990099] Using UIWebView
,2016-08-29 13:43:04.808 ThaliTest[744:990099] [CDVTimer][handleopenurl] 0.711024ms
,2016-08-29 13:43:04.816 ThaliTest[744:990099] [CDVTimer][intentandnavigationfilter] 7.335961ms
2016-08-29 13:43:04.817 ThaliTest[744:990099] [CDVTimer][gesturehandler] 0.388026ms
2016-08-29 13:43:04.817 ThaliTest[744:990099] [CDVTimer][TotalPluginStartup] 10.152996ms
,2016-08-29 13:43:10.772 ThaliTest[744:990099] Resetting plugins due to page load.
,2016-08-29 13:43:13.695 ThaliTest[744:990099] Finished load of: file:///var/mobile/Containers/Bundle/Application/060E89AE-C3B4-4447-9C26-7184CF969FAC/ThaliTest.app/www/index.html
,2016-08-29 13:43:13.926 ThaliTest[744:990099] JXcore Cordova plugin initializing
,2016-08-29 13:43:13.927 ThaliTest[744:990334] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.06209295988083
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
