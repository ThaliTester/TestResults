#### Test 82728424d2195a9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3A7F6C78-34B3-4BE3-8F3B-7588520FB6B1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3A7F6C78-34B3-4BE3-8F3B-7588520FB6B1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/179A9DE0-C902-4A63-BC1D-90D71D126C65/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63912"
,(lldb)     command script import "/tmp/3A7F6C78-34B3-4BE3-8F3B-7588520FB6B1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 20:51:50.577 ThaliTest[454:472597] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/89BAAB1B-9BD0-4B88-BD60-E23C1C1529C2/Library/Cookies/Cookies.binarycookies
,2016-08-25 20:51:51.052 ThaliTest[454:472597] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 20:51:51.053 ThaliTest[454:472597] Multi-tasking -> Device: YES, App: YES
,2016-08-25 20:51:51.075 ThaliTest[454:472597] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 20:51:52.979 ThaliTest[454:472597] Using UIWebView
,2016-08-25 20:51:52.986 ThaliTest[454:472597] [CDVTimer][handleopenurl] 0.365973ms
,2016-08-25 20:51:52.993 ThaliTest[454:472597] [CDVTimer][intentandnavigationfilter] 7.375956ms
2016-08-25 20:51:52.994 ThaliTest[454:472597] [CDVTimer][gesturehandler] 0.335991ms
2016-08-25 20:51:52.995 ThaliTest[454:472597] [CDVTimer][TotalPluginStartup] 9.833038ms
,2016-08-25 20:51:59.552 ThaliTest[454:472597] Resetting plugins due to page load.
,2016-08-25 20:52:02.679 ThaliTest[454:472597] Finished load of: file:///var/mobile/Containers/Bundle/Application/179A9DE0-C902-4A63-BC1D-90D71D126C65/ThaliTest.app/www/index.html
,2016-08-25 20:52:02.845 ThaliTest[454:472597] JXcore Cordova plugin initializing
2016-08-25 20:52:02.846 ThaliTest[454:472850] JXcore instance initializing
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
,*Native tests were not executed*
Total number of executed tests:  undefined
,Number of passed tests:  undefined
Number of failed tests:  undefined
Number of ignored tests:  undefined
,Total duration:  undefined
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
