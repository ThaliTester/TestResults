#### Test 82914073b1ed9e5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/15E80BBF-61A8-4AF1-89F1-5AC61EE5AC0D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/15E80BBF-61A8-4AF1-89F1-5AC61EE5AC0D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F4C58749-DD84-4881-A903-C6C6BB2212E7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56200"
,(lldb)     command script import "/tmp/15E80BBF-61A8-4AF1-89F1-5AC61EE5AC0D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 18:46:31.278 ThaliTest[960:1314958] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1CAD15A0-51DF-4F86-8EAA-B154E86241D3/Library/Cookies/Cookies.binarycookies
,2016-08-31 18:46:31.724 ThaliTest[960:1314958] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 18:46:31.726 ThaliTest[960:1314958] Multi-tasking -> Device: YES, App: YES
,2016-08-31 18:46:31.753 ThaliTest[960:1314958] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 18:46:33.475 ThaliTest[960:1314958] Using UIWebView
,2016-08-31 18:46:33.483 ThaliTest[960:1314958] [CDVTimer][handleopenurl] 0.455022ms
,2016-08-31 18:46:33.494 ThaliTest[960:1314958] [CDVTimer][intentandnavigationfilter] 9.733975ms
2016-08-31 18:46:33.495 ThaliTest[960:1314958] [CDVTimer][gesturehandler] 0.415027ms
2016-08-31 18:46:33.495 ThaliTest[960:1314958] [CDVTimer][TotalPluginStar,tup] 12.628019ms
,2016-08-31 18:46:39.729 ThaliTest[960:1314958] Resetting plugins due to page load.
,2016-08-31 18:46:42.510 ThaliTest[960:1314958] Finished load of: file:///var/mobile/Containers/Bundle/Application/F4C58749-DD84-4881-A903-C6C6BB2212E7/ThaliTest.app/www/index.html
,2016-08-31 18:46:42.740 ThaliTest[960:1314958] JXcore Cordova plugin initializing
2016-08-31 18:46:42.741 ThaliTest[960:1315210] JXcore instance initializing
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
Total number of executed tests:  22
Number of passed tests:  22
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  43.14486998319626
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
