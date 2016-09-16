#### Test 8552588742df921_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/325FCFE2-D76D-4A6C-869D-846DB40586CD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/325FCFE2-D76D-4A6C-869D-846DB40586CD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588742df921/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D93AE030-CF80-4305-AB10-072BE5E0066D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58563"
,(lldb)     command script import "/tmp/325FCFE2-D76D-4A6C-869D-846DB40586CD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 10:26:55.173 ThaliTest[782:972397] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A83F0592-133A-4AD5-B3DB-2A7A4948D35A/Library/Cookies/Cookies.binarycookies
,2016-09-16 10:26:55.430 ThaliTest[782:972397] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 10:26:55.432 ThaliTest[782:972397] Multi-tasking -> Device: YES, App: YES
,2016-09-16 10:26:55.454 ThaliTest[782:972397] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 10:26:55.932 ThaliTest[782:972397] Using UIWebView
,2016-09-16 10:26:55.939 ThaliTest[782:972397] [CDVTimer][handleopenurl] 0.376999ms
,2016-09-16 10:26:55.947 ThaliTest[782:972397] [CDVTimer][intentandnavigationfilter] 7.672012ms
2016-09-16 10:26:55.948 ThaliTest[782:972397] [CDVTimer][gesturehandler] 0.308990ms
2016-09-16 10:26:55.948 ThaliTest[782:972397] [CDVTimer][TotalPluginStartup,] 9.867013ms
,2016-09-16 10:27:00.978 ThaliTest[782:972397] Resetting plugins due to page load.
,2016-09-16 10:27:01.334 ThaliTest[782:972397] Finished load of: file:///var/containers/Bundle/Application/D93AE030-CF80-4305-AB10-072BE5E0066D/ThaliTest.app/www/index.html
,2016-09-16 10:27:01.685 ThaliTest[782:972397] JXcore Cordova plugin initializing
,2016-09-16 10:27:01.686 ThaliTest[782:972567] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 10:27:08.420 ThaliTest[782:972567] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 10:27:08.421 ThaliTest[782:972567] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 10:27:08.421 ThaliTest[782:972567,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 10:27:08.423 ThaliTest[782:972567] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 10:27:08.814 ThaliTest[782:972567] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003744006156921387
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
