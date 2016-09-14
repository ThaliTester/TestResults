#### Test 852639023cb0bc0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/967ED591-C5C7-4D70-8ED6-61FF1370884C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/967ED591-C5C7-4D70-8ED6-61FF1370884C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B4B6C451-F39F-4AD3-833D-F3A24D04C920/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50272"
,(lldb)     command script import "/tmp/967ED591-C5C7-4D70-8ED6-61FF1370884C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 00:22:53.770 ThaliTest[644:788397] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4AD9EAB1-D7A3-4D07-8681-7EA36717D860/Library/Cookies/Cookies.binarycookies
,2016-09-15 00:22:53.807 ThaliTest[644:788397] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 00:22:53.808 ThaliTest[644:788397] Multi-tasking -> Device: YES, App: YES
,2016-09-15 00:22:53.819 ThaliTest[644:788397] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 00:22:54.110 ThaliTest[644:788397] Using UIWebView
,2016-09-15 00:22:54.115 ThaliTest[644:788397] [CDVTimer][handleopenurl] 0.187993ms
,2016-09-15 00:22:54.119 ThaliTest[644:788397] [CDVTimer][intentandnavigationfilter] 3.485978ms
2016-09-15 00:22:54.120 ThaliTest[644:788397] [CDVTimer][gesturehandler] 0.164986ms
2016-09-15 00:22:54.120 ThaliTest[644:788397] [CDVTimer][TotalPluginStartup] 4.671037ms
,2016-09-15 00:22:59.519 ThaliTest[644:788397] Resetting plugins due to page load.
,2016-09-15 00:22:59.893 ThaliTest[644:788397] Finished load of: file:///var/containers/Bundle/Application/B4B6C451-F39F-4AD3-833D-F3A24D04C920/ThaliTest.app/www/index.html
,2016-09-15 00:23:00.394 ThaliTest[644:788397] JXcore Cordova plugin initializing
,2016-09-15 00:23:00.395 ThaliTest[644:788565] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1615beda0>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-15 00:23:22.824 ThaliTest[644:788397] BTM: attaching to BTServer
,2016-09-15 00:23:23.972 ThaliTest[644:788397] BTM: local device power state changed
2016-09-15 00:23:23.973 ThaliTest[644:788397] BTM: power is now off
,2016-09-15 00:23:24.696 ThaliTest[644:788397] BTM: local device power state changed
2016-09-15 00:23:24.697 ThaliTest[644:788397] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  52
Number of passed tests:  52
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  16.96005100011826
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
