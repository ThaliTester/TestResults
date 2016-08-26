#### Test 79896569ef47422_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79896569ef47422/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A0CB5EB8-3717-4159-8195-9D50F4C1A7D1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A0CB5EB8-3717-4159-8195-9D50F4C1A7D1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79896569ef47422/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79896569ef47422/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8EC469B5-FF91-43CC-B071-87E0C305CB47/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52403"
,(lldb)     command script import "/tmp/A0CB5EB8-3717-4159-8195-9D50F4C1A7D1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 18:18:32.991 ThaliTest[567:602754] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9B2E0C36-BEF3-4BC8-9BBB-C2EBE1AEE1D6/Library/Cookies/Cookies.binarycookies
,2016-08-26 18:18:33.397 ThaliTest[567:602754] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 18:18:33.398 ThaliTest[567:602754] Multi-tasking -> Device: YES, App: YES
,2016-08-26 18:18:33.421 ThaliTest[567:602754] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 18:18:35.076 ThaliTest[567:602754] Using UIWebView
,2016-08-26 18:18:35.083 ThaliTest[567:602754] [CDVTimer][handleopenurl] 0.530005ms
,2016-08-26 18:18:35.091 ThaliTest[567:602754] [CDVTimer][intentandnavigationfilter] 7.207036ms
2016-08-26 18:18:35.092 ThaliTest[567:602754] [CDVTimer][gesturehandler] 0.322998ms
2016-08-26 18:18:35.092 ThaliTest[567:602754] [CDVTimer][TotalPluginStartup,] 9.817004ms
,2016-08-26 18:18:41.039 ThaliTest[567:602754] Resetting plugins due to page load.
,2016-08-26 18:18:43.743 ThaliTest[567:602754] Finished load of: file:///var/mobile/Containers/Bundle/Application/8EC469B5-FF91-43CC-B071-87E0C305CB47/ThaliTest.app/www/index.html
,2016-08-26 18:18:43.981 ThaliTest[567:602754] JXcore Cordova plugin initializing
,2016-08-26 18:18:43.982 ThaliTest[567:602974] JXcore instance initializing
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
Total number of executed tests:  5
Number of passed tests:  5
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.006045997142791748
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
