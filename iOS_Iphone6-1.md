#### Test 85046911bd0d025_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E5023E37-BA90-4640-BD23-6C85CD978686/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E5023E37-BA90-4640-BD23-6C85CD978686/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A1C38F67-F957-429A-ACAC-EF85D31945B0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54973"
,(lldb)     command script import "/tmp/E5023E37-BA90-4640-BD23-6C85CD978686/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 13:37:44.250 ThaliTest[951:1477035] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/065469C8-C0E9-4C1A-B5EE-368B5C52A1ED/Library/Cookies/Cookies.binarycookies
,2016-09-20 13:37:44.480 ThaliTest[951:1477035] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 13:37:44.482 ThaliTest[951:1477035] Multi-tasking -> Device: YES, App: YES
,2016-09-20 13:37:44.502 ThaliTest[951:1477035] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 13:37:44.927 ThaliTest[951:1477035] Using UIWebView
,2016-09-20 13:37:44.933 ThaliTest[951:1477035] [CDVTimer][handleopenurl] 0.371039ms
,2016-09-20 13:37:44.941 ThaliTest[951:1477035] [CDVTimer][intentandnavigationfilter] 7.067025ms
2016-09-20 13:37:44.942 ThaliTest[951:1477035] [CDVTimer][gesturehandler] 0.301003ms
2016-09-20 13:37:44.942 ThaliTest[951:1477035] [CDVTimer][TotalPluginStartup] 9.217024ms
,2016-09-20 13:37:50.295 ThaliTest[951:1477035] Resetting plugins due to page load.
,2016-09-20 13:37:50.632 ThaliTest[951:1477035] Finished load of: file:///var/containers/Bundle/Application/A1C38F67-F957-429A-ACAC-EF85D31945B0/ThaliTest.app/www/index.html
,2016-09-20 13:37:50.969 ThaliTest[951:1477035] JXcore Cordova plugin initializing
2016-09-20 13:37:50.970 ThaliTest[951:1477810] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 13:37:57.655 ThaliTest[951:1477810] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 13:37:57.656 ThaliTest[951:1477810] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 13:37:57.656 ThaliTest[951:1477810] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 13:37:57.658 ThaliTest[951:1477810] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 13:37:58.064 ThaliTest[951:1477810] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.003422975540161133
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
