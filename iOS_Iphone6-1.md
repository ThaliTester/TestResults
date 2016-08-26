#### Test 82728424c383411_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424c383411/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AC75A658-601F-4EE8-8B48-BB5471BAD877/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AC75A658-601F-4EE8-8B48-BB5471BAD877/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424c383411/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424c383411/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/73FAACBE-B913-413B-B94B-09AA3D0332D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52849"
,(lldb)     command script import "/tmp/AC75A658-601F-4EE8-8B48-BB5471BAD877/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-26 10:50:36.094 ThaliTest[503:554753] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B25AA81B-D97C-433A-B695-3E05A5221290/Library/Cookies/Cookies.binarycookies
,2016-08-26 10:50:36.518 ThaliTest[503:554753] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 10:50:36.520 ThaliTest[503:554753] Multi-tasking -> Device: YES, App: YES
,2016-08-26 10:50:36.544 ThaliTest[503:554753] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 10:50:38.294 ThaliTest[503:554753] Using UIWebView
,2016-08-26 10:50:38.302 ThaliTest[503:554753] [CDVTimer][handleopenurl] 0.427008ms
,2016-08-26 10:50:38.310 ThaliTest[503:554753] [CDVTimer][intentandnavigationfilter] 8.315027ms
2016-08-26 10:50:38.311 ThaliTest[503:554753] [CDVTimer][gesturehandler] 0.337005ms
2016-08-26 10:50:38.312 ThaliTest[503:554753] [CDVTimer][TotalPluginStartup,] 10.797024ms
,2016-08-26 10:50:44.605 ThaliTest[503:554753] Resetting plugins due to page load.
,2016-08-26 10:50:47.455 ThaliTest[503:554753] Finished load of: file:///var/mobile/Containers/Bundle/Application/73FAACBE-B913-413B-B94B-09AA3D0332D5/ThaliTest.app/www/index.html
,2016-08-26 10:50:47.697 ThaliTest[503:554753] JXcore Cordova plugin initializing
2016-08-26 10:50:47.698 ThaliTest[503:554982] JXcore instance initializing
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
Total number of executed tests:  5
,Number of passed tests:  5
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.01063799858093262
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
