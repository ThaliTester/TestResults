#### Test 834440500e39eda_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7FAC4629-D0F5-4282-8C05-5D96AE068300/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7FAC4629-D0F5-4282-8C05-5D96AE068300/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8AA2971B-362B-4DFA-93E9-80D2BEF5E3C8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62924"
,(lldb)     command script import "/tmp/7FAC4629-D0F5-4282-8C05-5D96AE068300/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 10:30:50.941 ThaliTest[1352:2282934] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B04FC6FE-3A7E-4179-871D-1C40B6711213/Library/Cookies/Cookies.binarycookies
,2016-09-07 10:30:51.525 ThaliTest[1352:2282934] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 10:30:51.527 ThaliTest[1352:2282934] Multi-tasking -> Device: YES, App: YES
,2016-09-07 10:30:51.546 ThaliTest[1352:2282934] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 10:30:53.850 ThaliTest[1352:2282934] Using UIWebView
,2016-09-07 10:30:53.857 ThaliTest[1352:2282934] [CDVTimer][handleopenurl] 0.454962ms
,2016-09-07 10:30:53.865 ThaliTest[1352:2282934] [CDVTimer][intentandnavigationfilter] 7.434011ms
2016-09-07 10:30:53.866 ThaliTest[1352:2282934] [CDVTimer][gesturehandler] 0.348985ms
2016-09-07 10:30:53.867 ThaliTest[1352:2282934] [CDVTimer][TotalPluginStartup] 10.247946ms
,2016-09-07 10:31:01.272 ThaliTest[1352:2282934] Resetting plugins due to page load.
,2016-09-07 10:31:05.149 ThaliTest[1352:2282934] Finished load of: file:///var/mobile/Containers/Bundle/Application/8AA2971B-362B-4DFA-93E9-80D2BEF5E3C8/ThaliTest.app/www/index.html
,2016-09-07 10:31:05.382 ThaliTest[1352:2282934] JXcore Cordova plugin initializing
,2016-09-07 10:31:05.383 ThaliTest[1352:2283192] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
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
Total duration:  38.20149004459381
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
