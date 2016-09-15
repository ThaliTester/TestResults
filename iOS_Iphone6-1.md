#### Test 83627337176b608_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/ABB5893D-FE6B-401E-A19D-2441E813EF89/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/ABB5893D-FE6B-401E-A19D-2441E813EF89/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1B40288B-5D70-4C52-9B1D-009C438335FD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59228"
,(lldb)     command script import "/tmp/ABB5893D-FE6B-401E-A19D-2441E813EF89/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 16:28:32.997 ThaliTest[730:879293] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DBB9201E-3502-49F6-A302-4AB0F9E284BF/Library/Cookies/Cookies.binarycookies
,2016-09-15 16:28:33.248 ThaliTest[730:879293] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 16:28:33.250 ThaliTest[730:879293] Multi-tasking -> Device: YES, App: YES
,2016-09-15 16:28:33.272 ThaliTest[730:879293] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 16:28:33.644 ThaliTest[730:879293] Using UIWebView
,2016-09-15 16:28:33.649 ThaliTest[730:879293] [CDVTimer][handleopenurl] 0.275970ms
,2016-09-15 16:28:33.654 ThaliTest[730:879293] [CDVTimer][intentandnavigationfilter] 4.872978ms
2016-09-15 16:28:33.655 ThaliTest[730:879293] [CDVTimer][gesturehandler] 0.208974ms
2016-09-15 16:28:33.655 ThaliTest[730:879293] [CDVTimer][TotalPluginStartup] 6.442964ms
,2016-09-15 16:28:39.137 ThaliTest[730:879293] Resetting plugins due to page load.
,2016-09-15 16:28:39.405 ThaliTest[730:879293] Finished load of: file:///var/containers/Bundle/Application/1B40288B-5D70-4C52-9B1D-009C438335FD/ThaliTest.app/www/index.html
,2016-09-15 16:28:39.739 ThaliTest[730:879293] JXcore Cordova plugin initializing
,2016-09-15 16:28:39.740 ThaliTest[730:879497] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 16:28:46.509 ThaliTest[730:879497] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 16:28:46.509 ThaliTest[730:879497] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 16:28:46.509 ThaliTest[730:879497] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 16:28:46.511 ThaliTest[730:879497] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-15 16:28:46.901 ThaliTest[730:879497] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003755033016204834
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
