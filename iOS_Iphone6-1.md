#### Test 8291407379492e1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/17D2C27A-A2E8-4608-A2EF-5B05EB97D1FD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/17D2C27A-A2E8-4608-A2EF-5B05EB97D1FD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DF58E82F-827C-42E1-9EF3-48A016D7F4EB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52877"
,(lldb)     command script import "/tmp/17D2C27A-A2E8-4608-A2EF-5B05EB97D1FD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 10:22:26.480 ThaliTest[707:966048] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C0F3DB1-F870-40A8-ACB3-889642DDB516/Library/Cookies/Cookies.binarycookies
,2016-08-29 10:22:26.981 ThaliTest[707:966048] Apache Cordova native platform version 4.1.1 is starting.
2016-08-29 10:22:26.982 ThaliTest[707:966048] Multi-tasking -> Device: YES, App: YES
,2016-08-29 10:22:27.005 ThaliTest[707:966048] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 10:22:28.869 ThaliTest[707:966048] Using UIWebView
,2016-08-29 10:22:28.877 ThaliTest[707:966048] [CDVTimer][handleopenurl] 0.443995ms
,2016-08-29 10:22:28.885 ThaliTest[707:966048] [CDVTimer][intentandnavigationfilter] 7.696986ms
2016-08-29 10:22:28.886 ThaliTest[707:966048] [CDVTimer][gesturehandler] 0.382006ms
2016-08-29 10:22:28.886 ThaliTest[707:966048] [CDVTimer][TotalPluginStartup] 10.481000ms
,2016-08-29 10:22:35.443 ThaliTest[707:966048] Resetting plugins due to page load.
,2016-08-29 10:22:38.682 ThaliTest[707:966048] Finished load of: file:///var/mobile/Containers/Bundle/Application/DF58E82F-827C-42E1-9EF3-48A016D7F4EB/ThaliTest.app/www/index.html
,2016-08-29 10:22:38.987 ThaliTest[707:966048] JXcore Cordova plugin initializing
,2016-08-29 10:22:38.988 ThaliTest[707:966308] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
,Total number of executed tests:  20
Number of passed tests:  20
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  43.11865097284317
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
