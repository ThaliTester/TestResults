#### Test 79763830eafb657_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/00AC6852-B74D-4519-BDF1-2CE4C321BE95/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/00AC6852-B74D-4519-BDF1-2CE4C321BE95/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E896420-059A-4729-8F80-B39FAB09253A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58859"
,(lldb)     command script import "/tmp/00AC6852-B74D-4519-BDF1-2CE4C321BE95/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-26 12:01:15.772 ThaliTest[510:562292] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6F6293F-5945-4447-93A8-B5FF9DE618F8/Library/Cookies/Cookies.binarycookies
,2016-08-26 12:01:16.224 ThaliTest[510:562292] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 12:01:16.225 ThaliTest[510:562292] Multi-tasking -> Device: YES, App: YES
,2016-08-26 12:01:16.243 ThaliTest[510:562292] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 12:01:17.938 ThaliTest[510:562292] Using UIWebView
,2016-08-26 12:01:17.945 ThaliTest[510:562292] [CDVTimer][handleopenurl] 0.481009ms
,2016-08-26 12:01:17.953 ThaliTest[510:562292] [CDVTimer][intentandnavigationfilter] 7.140994ms
2016-08-26 12:01:17.954 ThaliTest[510:562292] [CDVTimer][gesturehandler] 0.316978ms
2016-08-26 12:01:17.954 ThaliTest[510:562292] [CDVTimer][TotalPluginStartup] 9.608984ms
,2016-08-26 12:01:23.930 ThaliTest[510:562292] Resetting plugins due to page load.
,2016-08-26 12:01:26.750 ThaliTest[510:562292] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E896420-059A-4729-8F80-B39FAB09253A/ThaliTest.app/www/index.html
,2016-08-26 12:01:26.951 ThaliTest[510:562292] JXcore Cordova plugin initializing
,2016-08-26 12:01:26.952 ThaliTest[510:562528] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 12:01:33.794 ThaliTest[510:562528] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 12:01:33.794 ThaliTest[510:562528] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 12:01:33.795 ThaliTest[510:562528] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 12:01:33.797 ThaliTest[510:562528] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 12:01:34.123 ThaliTest[510:562528] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.0121539831161499
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
