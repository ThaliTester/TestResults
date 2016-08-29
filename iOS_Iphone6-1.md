#### Test 829140738625595_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8531F337-C66B-4270-9388-A9684614C118/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8531F337-C66B-4270-9388-A9684614C118/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/74C42233-6A95-44BC-8F5D-440B1209D194/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55088"
,(lldb)     command script import "/tmp/8531F337-C66B-4270-9388-A9684614C118/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 11:05:02.870 ThaliTest[719:971672] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BAA0B9D5-3A8B-4C6F-B032-A22B9DF5A0B5/Library/Cookies/Cookies.binarycookies
,2016-08-29 11:05:03.307 ThaliTest[719:971672] Apache Cordova native platform version 4.1.1 is starting.
2016-08-29 11:05:03.308 ThaliTest[719:971672] Multi-tasking -> Device: YES, App: YES
,2016-08-29 11:05:03.329 ThaliTest[719:971672] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 11:05:05.217 ThaliTest[719:971672] Using UIWebView
,2016-08-29 11:05:05.224 ThaliTest[719:971672] [CDVTimer][handleopenurl] 0.523984ms
,2016-08-29 11:05:05.232 ThaliTest[719:971672] [CDVTimer][intentandnavigationfilter] 7.312000ms
2016-08-29 11:05:05.232 ThaliTest[719:971672] [CDVTimer][gesturehandler] 0.333011ms
2016-08-29 11:05:05.233 ThaliTest[719:971672] [CDVTimer][TotalPluginStartup] 9.911001ms
,2016-08-29 11:05:11.964 ThaliTest[719:971672] Resetting plugins due to page load.
,2016-08-29 11:05:14.966 ThaliTest[719:971672] Finished load of: file:///var/mobile/Containers/Bundle/Application/74C42233-6A95-44BC-8F5D-440B1209D194/ThaliTest.app/www/index.html
,2016-08-29 11:05:15.197 ThaliTest[719:971672] JXcore Cordova plugin initializing
,2016-08-29 11:05:15.198 ThaliTest[719:971912] JXcore instance initializing
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
,Total duration:  42.77026104927063
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
