#### Test 82914073856d1c8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A6CF2F69-108E-44AB-817D-8B6764D8FFBD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A6CF2F69-108E-44AB-817D-8B6764D8FFBD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D1B3F51E-2443-4582-A7B6-130FDA57DE77/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59598"
,(lldb)     command script import "/tmp/A6CF2F69-108E-44AB-817D-8B6764D8FFBD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-26 19:44:00.691 ThaliTest[584:613317] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/20676842-E354-43F6-A662-145D09507867/Library/Cookies/Cookies.binarycookies
,2016-08-26 19:44:01.190 ThaliTest[584:613317] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 19:44:01.192 ThaliTest[584:613317] Multi-tasking -> Device: YES, App: YES
,2016-08-26 19:44:01.213 ThaliTest[584:613317] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 19:44:03.044 ThaliTest[584:613317] Using UIWebView
,2016-08-26 19:44:03.051 ThaliTest[584:613317] [CDVTimer][handleopenurl] 0.386000ms
,2016-08-26 19:44:03.058 ThaliTest[584:613317] [CDVTimer][intentandnavigationfilter] 7.354021ms
2016-08-26 19:44:03.059 ThaliTest[584:613317] [CDVTimer][gesturehandler] 0.353992ms
2016-08-26 19:44:03.060 ThaliTest[584:613317] [CDVTimer][TotalPluginStartup] 9.651005ms
,2016-08-26 19:44:09.608 ThaliTest[584:613317] Resetting plugins due to page load.
,2016-08-26 19:44:12.513 ThaliTest[584:613317] Finished load of: file:///var/mobile/Containers/Bundle/Application/D1B3F51E-2443-4582-A7B6-130FDA57DE77/ThaliTest.app/www/index.html
,2016-08-26 19:44:12.738 ThaliTest[584:613317] JXcore Cordova plugin initializing
,2016-08-26 19:44:12.739 ThaliTest[584:613555] JXcore instance initializing
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
Total number of executed tests:  20
Number of passed tests:  20
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  42.03948903083801
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
