#### Test 83627337176b608_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1A82E4D2-D226-4E35-AB17-2D81CEA1C552/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1A82E4D2-D226-4E35-AB17-2D81CEA1C552/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/74E788AE-BC3F-4B23-83FB-258FBB8C60C1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55841"
,(lldb)     command script import "/tmp/1A82E4D2-D226-4E35-AB17-2D81CEA1C552/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 10:00:51.636 ThaliTest[775:969590] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E7034AA7-7900-44E6-96B6-7DB6CC0998C4/Library/Cookies/Cookies.binarycookies
,2016-09-16 10:00:51.996 ThaliTest[775:969590] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 10:00:51.998 ThaliTest[775:969590] Multi-tasking -> Device: YES, App: YES
,2016-09-16 10:00:52.024 ThaliTest[775:969590] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 10:00:52.525 ThaliTest[775:969590] Using UIWebView
,2016-09-16 10:00:52.531 ThaliTest[775:969590] [CDVTimer][handleopenurl] 0.354946ms
,2016-09-16 10:00:52.538 ThaliTest[775:969590] [CDVTimer][intentandnavigationfilter] 7.058978ms
2016-09-16 10:00:52.539 ThaliTest[775:969590] [CDVTimer][gesturehandler] 0.298977ms
2016-09-16 10:00:52.539 ThaliTest[775:969590] [CDVTimer][TotalPluginStartup] 9.207010ms
,2016-09-16 10:00:57.984 ThaliTest[775:969590] Resetting plugins due to page load.
,2016-09-16 10:00:58.401 ThaliTest[775:969590] Finished load of: file:///var/containers/Bundle/Application/74E788AE-BC3F-4B23-83FB-258FBB8C60C1/ThaliTest.app/www/index.html
,2016-09-16 10:00:58.779 ThaliTest[775:969590] JXcore Cordova plugin initializing
,2016-09-16 10:00:58.780 ThaliTest[775:969782] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 10:01:05.436 ThaliTest[775:969782] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 10:01:05.436 ThaliTest[775:969782] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 10:01:05.436 ThaliTest[775:969782] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 10:01:05.438 ThaliTest[775:969782] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 10:01:05.822 ThaliTest[775:969782] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003695964813232422
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
